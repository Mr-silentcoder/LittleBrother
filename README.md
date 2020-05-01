LittleBrother
=

LittleBrother is an information collection tool (OSINT) which aims to carry out research on a French, Swiss, Luxembourg or Belgian person. It provides various modules that allow efficient searches. LittleBrother does not require an API key or login ID.

![](https://i.ibb.co/YdvfVPw/Capture.png)

Disclaimer
=
LittleBrother was developed to do research on yourself and to see the private and sensitive information that can be left behind on social networks. I in no way encourage the use of this tool on someone other than yourself or to use this tool improperly. The authors of LittleBrother cannot be held responsible for the use of its tool.


Installation sur Linux
=
You must have `git` and `python3` installed on your machine
```
    sudo apt install git python3 #sur les distributions utilisant APT (comme la famille Debian)
    git clone https://github.com/Lulz3xploit/LittleBrother
    cd LittleBrother
    python3 -m pip install -r requirements.txt
```    

Execution Linux
=
In the LittleBrother directory, launch this command to be able to launch LittleBrother:
```
python3 LittleBrother.py
```

Installation sur Windows
=
- 1. Download [LittleBrother](https://github.com/lulz3xploit/LittleBrother/archive/master.zip)
- 2. Install Python from the Windows Store
- 4. Dezipper LittleBrother (master.zip)
- 5. open `CMD` and go to the directory **`LittleBrother-master`** via la commande `cd`.
     P.ex: 
```
cd Desktop\
cd LittleBrother-master\
``` 
and run:
```
    python3 -m pip install -r requirements.txt
```

Launch LittleBrother from Windows:
=
- Go to the directory **LittleBrother-master** as at its installation and execute the command: 
```
python3 LittleBrother.py
```

Discord
=
If you have questions, ideas, problems regarding LittleBrother or if you just want to follow the progress of this project.  
- [Serveur Discord](https://discord.gg/r8GvsYM)

News version 6.0
=
- En plus (+)
	- A 'requirements.txt' file has been added.
	- A new interface.
	- A new OSINT module has been added. The 'Profiler' module allows you to create a profile and retrieve information on user-defined sites, save this data and display the latest posts published on the networks (filtered according to publication dates).
	- New search services (Directories) have been added depending on the user's location. LittleBrother uses your IP to determine the country you are in. In no case will your IP or other private information be shared. You can choose a country other than yours to centralize your research.
	- Instagram and LinkedIn search integrated into 'Person Lookup'.
	- A new module 'Research employees' which allows to find people via a company and a city.
	- The Instagram and Facebook information search modules have been improved to extract more information.  

- En less (-)
	- Some python libraries (dnspython, socket and smtplib) have been removed for this version.
	- 'Social engineering tool' has been modified for 'Other tool', it only includes the brute force module of a Hash.
	- 'Spam Email' and 'SMS' modules have been removed from LittleBrother.


Compatible
=
- Windows
- MacOS
- Linux

Python version:
=
- Python3

Modules Python
=
- requests
- bs4
- terminaltables
- colorama

Fonctionnalites
=
 - Lookup:
	- Phone lookup
	- Email lookup
	- Last name / First name lookup
	- Surname lookup
	- Addresse lookup
	- Mail ip locator
	- Ip locator
	- Bssid locator
	- Exif read
	- Google search
	- Twitter
	- Instagram
	- Facebook
	- LinkedIn employee search (New !)
	- Hash Bruteforce (New !)

 - Autre outils:

	- Hash Bruteforce

- Profiler (New !)
	- Profiler an profile
	- Database management
	- Profile creator

Contributors
=
❤️ [H3L](https://github.com/lrhel) ❤
