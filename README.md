# katfetch
A modular, hackable, and minimal fetch script written in Bash

# How do I install katfetch?
First, install the dependencies: xrandr, figlet and bash.
Then, git clone this repo to somewhere like ~/.katfetch, copy the shell script to /usr/bin/katfetch
and copy
the example config to ~/.config/katfetch/.
If you're stubborn replace doas with the bloated sudo.
```
git clone https://github.com/egor4ka/katfetch ~/.katfetch
cd ~/.katfetch
mkdir ~/.config/katfetch/
cp ./config ~/.config/katfetch/
doas cp ./katfetch /usr/bin/katfetch
```

# Screenshots
![image](https://user-images.githubusercontent.com/50289495/154300990-7a76ab6d-d213-468c-98a5-00ce7a3e961f.png)
![image](https://user-images.githubusercontent.com/50289495/154301058-5f3a99ab-bb0a-4e10-9530-f6adef1741e0.png)
![image](https://user-images.githubusercontent.com/50289495/154301093-7e098a79-d956-4e0f-abc5-7e1658a8b71e.png)

# Usage
Flags:
-f or --config: specify config file path
-g or --force-figlet: force figlet instead of ascii
-l or --left: print on left
-c or --center: print on center
-a or --art: specify ascii art

# Configuration
You can edit the ~/.config/katfetch/config or your own config file to reorder functions, add your own functions, or remove some.
You can also set ascii art, color and to be centered or not.
