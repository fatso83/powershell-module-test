# Powershell module loading test

This is a demo of how to load a module in Powershell.
It also shows a bug in the Unix powershell implementation of version 6 (alpha, build 12),
as it never finds the module.
It works perfectly in Windows.

## Running it
```
powershell -File bar-test.ps1

Oh, hello there. You are now loading the Bar module  

Bar says hello
```
