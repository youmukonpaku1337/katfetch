# shellfetch
A modular, hackable, and minimal fetch script written in Bash

# How do I install shellfetch?
First, install the dependencies: xrandr, figlet and bash.
Then, git clone this repo to somewhere like ~/.shellfetch, symlink the shell script to /usr/bin/shellfetch
and copy
the example config to ~/.config/shellfetch/.
If you're stubborn replace doas with the bloated sudo.
```
git clone https://github.com/egor4ka/shellfetch ~/.shellfetch
cd ~/.shellfetch
mkdir ~/.config/shellfetch/
cp ./config ~/.config/shellfetch/
doas ln -s ./shellfetch /usr/bin/shellfetch
```

# Screenshots
![image](https://user-images.githubusercontent.com/50289495/154148633-ff8cc514-b9a9-45bc-b413-01e8283ff82a.png)
![image](https://user-images.githubusercontent.com/50289495/154148717-d12cd636-38b2-4c08-b14f-45c71032584b.png)
![image](https://user-images.githubusercontent.com/50289495/154149197-93b46c70-4f40-417e-b164-76872ff86671.png)

# Configuration
You can edit the ~/.config/shellfetch/config file to reorder functions, add your own functions, or remove some.
You can also set ascii art, color and to be centered or not.
