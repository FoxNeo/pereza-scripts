# Windows

First we create a folder and in this folder we will save all scripts with the extension **.bat**

```batch
mkdir scripts
```
Now we are going to set an environment variable with scripts folder, if you don't know how to create it here in [example](https://www.computerhope.com/issues/ch000549.htm)

## batch file .bat
Now we can create our .bat file, for example this file opens the Windows explorer with the folder. You can type this from the Windows cmd folder will open.

```batch
@echo off
echo Opening scripts directory...
start "." "C:\scripts"
```
Save into file, now open a new cmd windows and type:

```batch
scripts
```
You can see that no matter what path the windows cmd is, you can type scripts and the windows explorer will open your scripts folder.
