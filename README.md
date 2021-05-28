# WOWception v0.123456789
A bashscript for (offline) viewing and (mass) tipping Wownero memes from https://suchwow.xyz.  
Based on sxiv, several command line utils and WOWlet.

![wowception](https://github.com/smartypete/WOWception/blob/main/wowception.jpg)

The script downloads all memes and donation addresses to your hard-disk. It's also possible to display an alert upon new meme arrivals.

![wowality](https://github.com/smartypete/WOWception/blob/main/wowality.jpg)

WOWALITY in sxiv's thumbnail view.

![wowwork](https://github.com/smartypete/WOWception/blob/main/wowwork.jpg)

Das it mane!

# Debian/Ubuntu
Get all the tools
```
sudo apt install xdotool sxiv wmctrl elinks w3m bc lolcat git
git clone https://github.com/smartypete/WOWception
```
Download WOWlet, follow instructions to create a wallet and leave it open.
Get it here: https://git.wownero.com/wowlet/wowlet/releases

Now fire up WOWception in the terminal and tip shitty memes like you never did before!
(Make sure to have enough output points if you want to let it rain in bulk. Don't touch your input devices during automatic sending to >15 addresses or it can fuck up... run WOWlet in a seperate X session to avoid.)
