# MVN Installation

## MAC 

Step 1:
- Download maven archive (tar.gz) file from below link
https://maven.apache.org/download.cgi

Step 2: After downloading run following command
Run below command in folder containing Downloaded file.
```
tar -xvf apache-maven-3.8.7.bin.tar.gz
```

Step 3: Set Maven path to your extracted folder in your .zshrc file <br>
*NOTE : if you are using .bash_profile then set your path in that particular file

```
export PATH="$PATH:/Users/username/Downlands/apache-maven-3.8.7/bin"
```

## Windows

Step 1:
- Donwload maven arhicve (bin.zip) from below link
https://maven.apache.org/download.cgi

Step 2:
- Extract zip file to a specific folder

i.e C:\Program Files\Maven\apache-maven-3.8.7

Step 3:
- Goto to Enviroment Variables section in System Properties window and add <b>'MAVEN_HOME'<b>
  variable
- Add path that was used in Step 2 to the variable's value.
