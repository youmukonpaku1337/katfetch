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

# Configuration
You can edit the ~/.config/katfetch/config file to reorder functions, add your own functions, or remove some.
You can also set ascii art, color and to be centered or not.
