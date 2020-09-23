<div align="center">

## Execute another Program/File with one line of code\.


</div>

### Description

This code executes another file/program from within your Delphi application. Can be quite handy!
 
### More Info
 
None i know of!


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Niel Corns](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/niel-corns.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |Delphi 5, Delphi 4
**Category**       |[Windows API Call/ Explanation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-api-call-explanation__7-39.md)
**World**          |[Delphi](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/delphi.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/niel-corns-execute-another-program-file-with-one-line-of-code__7-120/archive/master.zip)





### Source Code

```
Uses ShellAPI (Put this into your Uses Section!)
Put this into a button etc...
ShellExecute(0,nil,'C:\WINDOWS\CALC.EXE',nil,nil,1);
```

