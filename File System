<!---
  Name          : Exersise #1 File System
  Project       : Linux-Basics
  Description   : Introduction to Linux File System
  Creation Date : 12 November 23
  Author        : Samhain
  Link          : https://github.com/SunTzusTeacher/Linux-Basics
--->
# File System
### 
Use the `ls` command from the root (`/`) directory to explore the directory structure of Linux. Move to each of the directories with the `cd` command and run `pwd` to verify where you are in the directory structure.

---

````shell
root@kali:/# ls -l
total 68
lrwxrwxrwx   1 root root     7 Sep  10 13:00 bin -> usr/bin
drwxr-xr-x   3 root root  4096 Nov  12 13:44 boot
drwxr-xr-x  18 root root  3280 Nov  12 13:59 dev
drwxr-xr-x 178 root root 12288 Nov  12 13:59 etc
drwxr-xr-x   3 root root  4096 Sep  10 13:15 home
lrwxrwxrwx   1 root root    33 Nov  12 13:41 initrd.img -> boot/initrd.img-6.5.0-kali3-amd64
lrwxrwxrwx   1 root root    33 Sep  10 13:01 initrd.img.old -> boot/initrd.img-6.1.0-kali5-amd64
lrwxrwxrwx   1 root root     7 Sep  10 13:00 lib -> usr/lib
lrwxrwxrwx   1 root root     9 Sep  10 13:00 lib32 -> usr/lib32
lrwxrwxrwx   1 root root     9 Sep  10 13:00 lib64 -> usr/lib64
drwx------   2 root root 16384 Sep  10 13:00 lost+found
drwxr-xr-x   3 root root  4096 Sep  10 13:00 media
drwxr-xr-x   2 root root  4096 Sep  10 13:00 mnt
drwxr-xr-x   2 root root  4096 Oct  23 18:52 opt
dr-xr-xr-x 220 root root     0 Nov  12 13:08 proc
drwx------   3 root root  4096 Nov  12 13:42 root
drwxr-xr-x  34 root root   820 Nov  12 13:36 run
lrwxrwxrwx   1 root root     8 Sep  10 13:00 sbin -> usr/sbin
drwxr-xr-x   3 root root  4096 Sep  10 12:10 srv
dr-xr-xr-x  13 root root     0 Nov  12 13:08 sys
drwxrwxrwt  15 root root  4096 Nov  12 13:59 tmp
drwxr-xr-x  14 root root  4096 Oct  23 18:31 usr
drwxr-xr-x  12 root root  4096 Sep  10 13:02 var
lrwxrwxrwx   1 root root    30 Nov  12 13:41 vmlinuz -> boot/vmlinuz-6.5.0-kali3-amd64
lrwxrwxrwx   1 root root    30 Sep  10 13:01 vmlinuz.old -> boot/vmlinuz-6.1.0-kali5-amd64
root@kali:/# cd boot/
root@kali:/boot# pwd
/boot
root@kali:/boot# cd /dev/
root@kali:/dev# pwd
/dev
root@kali:/dev# cd /etc/
root@kali:/etc# pwd
/etc
root@kali:/etc# cd /home/
root@kali:/home# pwd
/home
root@kali:/home# cd /lost+found/
root@kali:/lost+found# pwd
/lost+found
root@kali:/lost+found# cd /media/
root@kali:/media# pwd
/media
root@kali:/media# cd /mnt/
root@kali:/mnt# pwd
/mnt
root@kali:/mnt# cd /opt/
root@kali:/opt# pwd
/opt
root@kali:/opt# cd /proc/
root@kali:/proc# pwd
/proc
root@kali:/proc# cd /root/
root@kali:~# pwd
/root
root@kali:~# cd /run/
root@kali:/run# pwd
/run
root@kali:/run# cd /srv/
root@kali:/srv# pwd
/srv
root@kali:/srv# cd /sys/
root@kali:/sys# pwd
/sys
root@kali:/sys# cd /tmp/
root@kali:/tmp# pwd
/tmp
root@kali:/tmp# cd /usr/
root@kali:/usr# pwd
/usr
root@kali:/usr# cd /var/
root@kali:/var# pwd
/var
````
### This teaches you how to jump around the directories and check where you are.
---


###
Use the `whoami` command to verify which user you are logged in as.

---

````shell
kali@kali:~$ whoami
kali
````
### This is useful for identifying what user you are.
---


###
Use the `locate` command to find wordlists that can be used for password cracking.

---

````shell
kali@kali:~$ locate wordlists
/etc/theHarvester/wordlists
/etc/theHarvester/wordlists/dns-big.txt
/etc/theHarvester/wordlists/dns-names.txt
/etc/theHarvester/wordlists/dorks.txt
/etc/theHarvester/wordlists/general
/etc/theHarvester/wordlists/names_small.txt
/etc/theHarvester/wordlists/general/common.txt
--snip--
/var/lib/dpkg/info/wordlists.prerm
````
### locate allows for you to find the directory path to things.
---


### 
Use the `cat` command to create a new file and then append to that file. Keep in mind that `>` redirects input to a file and `>>` appends to a file.

---

````shell
kali@kali:~$ cat > newfile
This is my new file.
kali@kali:~$ cat >> newfile
This is my appendage.
kali@kali:~$ cat newfile
This is my new file.
This is my appendage.
````

---


### 
Create a new directory called `hackerdirectory` and create a new file that directory named `hackedfile`. Now copy that file to your `/root` directory and rename it `secretfile`.

---

````shell
root@kali:/home/kali# mkdir hackerdirectory
root@kali:/home/kali# touch hackerdirectory/hackedfile
root@kali:/home/kali# cp hackerdirectory/hackedfile /root/secretfile
````

---
