# Linux

## Config Maven as environment variable
1. Download maven binaries and extract the folder
2. Copy the path to maven for example ~/maven/bin
3. Open a terminal and type:
```bash
$ nano .bashrc 
```
Add this to the file **.bashrc:**
```
PATH=~/maven/bin:$PATH
```
4. After store type this to refresh shell
```bash
$ . ~/.bashrc
```
5. To test if mvn works type:
```bash
$ mvn -version
```