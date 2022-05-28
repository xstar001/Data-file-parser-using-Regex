# Data-file-parser-using-Regex
◆ This tool parses the data file using Regex. 

◆ The kernel of the tool is wrapped into a C# Dll (DataFileParser.dll) based on .Net Core 3.1, so that you can use it in either C# or Matlab. 

◆ This tool will parse the data file using specified Regex and store the data entries into a buffer. 

◆ Examples of Regex: 

    If the data file contains entries in the form of XXX=XXX, then the regex is: \w*\s*=\s*(-)?\d*.\d*\W
  
    If the data entries are just numbers, then the regex is: \S(-)?\d*(.\d*([e,E](-)?\d*)?\S\W)?
  
    If you want to retrieve a specify data item (e.g. Cltot =   0), then the regex will be: Cltot\s*=\s* (-)?\w*
  
◆ To learn to use or test your Regex, just run "DataFileParserShell.exe". 

◆ Click the "Help" button to show help in the console. 
