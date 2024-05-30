# cve-2016-5195-DirtyCOW
* This exploit using ptrace(POKETEXT) and change /etc/passwd

#Compile 
```
gcc exploit.c -o exploit -lpthread -lcrypt
```

#Use
```
./exploit [password]
```
* if you empty password field it used default password : 1234
