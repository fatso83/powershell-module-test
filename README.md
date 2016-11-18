# Powershell module loading test

This is a demo of how to load a module in Powershell.
<s>It also shows a bug in the Unix powershell implementation of version 6 (alpha, build 12),
as it never finds the module.</s>. 

It works perfectly in Windows, Mac and Linux. If you cannot get module loading to work in 
unices like OS X ensure that you write the module path _in all upper case_.  See
PowerShell/PowerShell#2677 for background info on `PSMODULEPATH`.

## Running it
```
powershell -File bar-test.ps1

Oh, hello there. You are now loading the Bar module  

Bar says hello
```
