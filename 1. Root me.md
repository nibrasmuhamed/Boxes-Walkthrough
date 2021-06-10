# Root me 🧭
Names | Details
--------|-----
Source | tryhackme
Level     | easy
Os | linux

**Notes :**




## Gaining Access 😉

- PHP reverse shell uploaded as .php5 extesion
- netcat to listen on port



## Maintaining Access 🥷
- SUID Permission
	- /usr/bin/python


## Important commands 🔥
- find / -perm /4000
	- `/usr/bin/python -c 'import os; os.setuid(0); os.system("/bin/sh")'`

## Post Exploitation ✴️
- User flag : /home/user
- Root flag : /root/root
## Tips 💡
- it's possible to bypass .php Extesions filter by renaming it as .php5
- used python script for privilege escalation 


--------------------------------
**By Nibras Muhammed** 🤓🖥️






