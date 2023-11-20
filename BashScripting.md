<!---
  Name          : Bash Scripting
  Project       : Linux-Basics
  Description   : Introduction to Bash Scripting
  Creation Date : 20 Novembber 2023
  Author        : Samhain
  Link          : https://github.com/SunTzusTeacher/Linux-Basics/
--->

# Bash Scripting
---
### Using your text editor of choice, begin with a shebang **#!** to tell the OS what interpreter you want to use. It will be followed by **/bin/bash**.

````
#! /bin/bash
````

---
### Now we'll add a comment for the script and make it output a statement.

````
#! /bin/bash

# This script should output a desired statement in the terminal.
echo "I am a scripting sevant!"
````

### For the purposes of this exersise I will be saving it as ScriptSevant. **Note** that you should save it with no extension.

---
### To make execcution simple well change the permissions to the file to be able to execute for users, groups, and others.

````shell
kali >chmod 755 ScriptSevant
````

---

### Now lets Run it.
````shell
kali >./ScriptSevant
kali > I am a scripting sevant!
````

---
