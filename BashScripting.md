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

### For the purposes of this exersise I will be saving it as **ScriptSevant**. **Note** that you should save it with no extension.

---
### To make execution simple well change the permissions to the file to be able to execute for users, groups, and others.

````shell
kali >chmod 755 ScriptSevant
````

---

### Now lets Run it!
````shell
kali >./ScriptSevant
kali >I am a scripting sevant!
````

---

### Now were going to add some functionality with variables.

````
#! /bin/bash

# This is script builds on ScriptSevant adding variables to increase functionality.

# Prompt user for input.
echo "Who are you?"

# Recieve user input.
read name

# Prompt user for input.
echo "How old are you?"

# Recieve user input
read age

# Output statement with user input included
echo "I am $name and I am $age and I am a scripting sevant!"
````

### This script is probbably a bit over commented, but its good to start a good habit of commenting code. We will save this script as **ScriptSevant_v1** . Now lets run the new script!

````shell
kali >./ScriptSevant_v1
kali >What is your name?
kali >Bob
kali >How old are you?
kali >timeless
kali >I am Bob and I am timeless and I am a scripting sevant!
````
---






