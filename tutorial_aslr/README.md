# Tutorial: ASLR

## Category: Binary Exploitation

## Description
```
The tutorial set of challenges are basic binary exploitation challenges designed to teach people various binary exploitation techniques. The recommended order to complete these challenges is ret2win, ROP, Shellcode, Canary, ASLR. These challenges can be completed without downloading and analyzing the binaries; however, they have been provided. If you need help with any of these challenges, feel free to reach out in the Discord.
```

### Flag: flag{342db1252faa6a2984b4935e0b4f1455}

---
# Docker
Run the challenge with docker.  
```bash
$ docker build -t tutorial_aslr .
$ docker run -p 9999:9999 tutorial_aslr
```
Connect with netcat.
```bash
$ nc localhost 9999
```
