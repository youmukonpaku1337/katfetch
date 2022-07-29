# katfetch
A modular, hackable, and minimal fetch script written in Bash

# How do I install katfetch?

Automatic (Recommended): 
```sudo wget https://raw.githubusercontent.com/terminalmaid/katfetch/main/katfetch -q -O /usr/bin/katfetch;chmod +x /usr/bin/katfetch```

Manual:
First, install the dependencies: xrandr, figlet, playerctl and bash.
Then, git clone this repo to somewhere like ~/.katfetch and copy the shell script to /usr/bin/katfetch.
If you're stubborn replace doas with the bloated sudo.
```
git clone https://github.com/egor4ka/katfetch ~/.katfetch
cd ~/.katfetch
doas cp ./katfetch /usr/bin/katfetch
```

# Screenshots
![image](https://user-images.githubusercontent.com/50289495/154300990-7a76ab6d-d213-468c-98a5-00ce7a3e961f.png)
![image](https://user-images.githubusercontent.com/50289495/154301058-5f3a99ab-bb0a-4e10-9530-f6adef1741e0.png)
![image](https://user-images.githubusercontent.com/50289495/154301093-7e098a79-d956-4e0f-abc5-7e1658a8b71e.png)

# Usage
```
you can use the configpath env var to specify config path
flags:
-g or --force-figlet: force figlet instead of ascii
-l or --left: print on left
-c or --center: print on center
-a or --art: specify ascii art
-h or --help: help
```

# Configuration
You can edit the ~/.config/katfetch/config or your own config file to reorder functions, add your own functions, or remove some.
You can also set ascii art, color and to be centered or not.
Note that configs other than ~/.config/katfetch/config should not contain the if else part since that recurses

# License
This lil' script is licensed under the WTFPL, a great license that allows you to pretty much fuckin' anything. Get more info at http://www.wtfpl.net/
![logo-220x1601](https://user-images.githubusercontent.com/50289495/155028333-17da751d-d7b8-421b-9e79-eebe3b00ab54.png)

Note that this project also has the MIT license included for compatibility.

# Credit
Thanks to me0wing-katt0 (Egor Scherbakov), TruncatedDinosour (Ari Archer) and The-Repo-Club (Wayne Wesley)

hjklhjkl
