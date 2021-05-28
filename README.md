# WOWception v0.123456789
A bashscript for (offline) viewing and (mass) tipping Wownero memes from https://suchwow.xyz.  
Based on sxiv, several command line utils and WOWlet.

![wowception](https://github.com/smartypete/WOWception/blob/main/wowception.jpg)

Thumbnail mode (WOWALITY) in sxiv:
![wowality](https://github.com/smartypete/WOWception/blob/main/wowality.jpg)

# Installation on Debian/Ubuntu
Get all the tools:
```
sudo apt install xdotool sxiv wmctrl elinks w3m bc lolcat zenity git
git clone https://github.com/smartypete/WOWception.git
```
Download WOWlet, follow instructions to create a wallet and leave it open.
Get it here: https://git.wownero.com/wowlet/wowlet/releases

Make sure to have enough output points if you want to let it rain in bulk. Don't touch your input devices during automatic sending to >15 addresses or it can fuck up... run WOWlet in a seperate X session to avoid.

Navigate to your WOWception directory and set executable flags:
```
cd your/path/to/glory
chmod +x wowception memechecker
```
Now fire up WOWception in the terminal with ```./wowception``` and tip shitty memes like you never did before! Das it mane!
