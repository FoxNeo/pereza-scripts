# Automate Tomcat

## Deploy WAR file from terminal
Open your terminal and edit your **.bashrc** file. Use alias to have access to your command everywhere like a program for example
```bash
alias webprojectdeploy="/home/user/webproject/target/webproject.war /opt/tomcat/webapps"
```

Save changes and refresh your bash:
```bash
$ . .bashrc
```
Now you can just open a terminal everywhere and just type:
```
$ webprojectdeploy
```
This save a lot of time

<hr>

## Start tomcat everywhere from terminal 
If you are working on your code with vim or other terminal code editor, you want to start fast your Tomcat instead to go to the CATALINA Folder and start **catalina.sh**. You can for example just type tomcatrun and tomcat will be started. Open your .bashrc file and add:
```bash
alias tomcatrun="cd /opt/tomcat/bin && ./catalina.sh run"
```
Save changes and refresh your bash:
```bash
$ . .bashrc
```
Now you can just open a terminal everywhere and just type:
```
$ tomcatrun
```
