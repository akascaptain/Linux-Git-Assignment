To run a command as administrator (user "root"), use "sudo <command>".
See "man sudo_root" for details.

akashshinde@Devadatta:~$ touch myfile.txt
akashshinde@Devadatta:~$ ls -l myfile.txt
-rw-r--r-- 1 akashshinde akashshinde 0 Jun  8 15:37 myfile.txt
akashshinde@Devadatta:~$ chmod u+x myfile.txt                    //Give execute permission to the owner
akashshinde@Devadatta:~$ chmod g-r myfile.txt                   //Remove read permission from group
akashshinde@Devadatta:~$ chmod o+w myfile.txt                   //Add write permission to others

akashshinde@Devadatta:~$ ls -l myfile.txt
-rwx---rw- 1 akashshinde akashshinde 0 Jun  8 15:37 myfile.txt

akashshinde@Devadatta:~$
