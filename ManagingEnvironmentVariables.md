<!---
  Name          : Managing Environment Variables
  Project       : Linux-Basics
  Description   : Introduction to managing envirorment variables
  Creation Date : 18 September 2023
  Author        : Samhain
  Link          : https://github.com/SunTzusTeacher/Linux-Basics
--->


# Managing Environment Variables

### View all of your environment variables with the `more` command.

---

````shell
kali@kali:~$ set | more
BASH=/bin/bash
BASHOPTS=checkwinsize:cmdhist:complete_fullquote:expand_aliases:extglob:ext
quote:force_fignore:globasciiranges:histappend:interactive_comments:progcom
p:promptvars:sourcepath
BASH_ALIASES=()
BASH_ARGC=([0]="0")
BASH_ARGV=()
--snip--
}
````

---


### Use the `echo` command to view the `HOSTNAME` variable.

---

````shell
kali@kali:~$ echo $HOSTNAME
kali
````

---


### Find a method to change the slash (`/`) to a backslash ('\') in the faux Microsoft `cmd PS1` example (see Listing 7.2).

---

````shell
kali@kali:~$ PS1='C:\\\W> '
C:\~> cd /home
C:\home>
````

---


### Create a variable names `MYNEWVARIABLE` and put your name in it.

---

````shell
kali@kali:/home$ MYNEWVARIABLE=amenasec
````

---


### Use `echo` to view the contents of `MYNEWVARIABLE`.

---

````shell
kali@kali:/home$ echo $MYNEWVARIABLE
amenasec
````

---


### Export `MYNEWVARIABLE` so that it's available in all environments.

---

````shell
kali@kali:/home$ export MYNEWVARIABLE
````

---


### Use the echo command to view the contents of the `PATH` variable.

---

````shell
kali@kali:/home$ echo $PATH
/usr/local/bin:/usr/bin:/bin:/usr/local/games:/usr/games
````

---


### Add your home directory to the `PATH` variable so that any binaries in your home directory can be used in any directory.

---

````shell
kali@kali:/home$ PATH=$PATH:/home/kali
````

---


### Change your `PS1` variable to "World's Greatest Hacker:".

---

````shell
kali@kali:/home$ PS1="World's Greatest Hacker: "
World's Greatest Hacker:
````

---
