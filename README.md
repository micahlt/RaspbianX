# RaspbianX
This is a modified version of Raspbian Buster (Bare-minimal desktop version) for the Raspberry Pi using the Ubuntu MATE desktop environment with a fully custom theme and icon set.

# RaspbianX is for power users and is NOT reccomended for new Raspberry Pi users.
RaspbianX is designed for more advanced users or for those who want an aesthetically pleasing desktop experience. This is for looks, not for user friendliness. (Or do whatever the duck you want. I don't care, this comment has the same strength as those "click here if you are above 18 years old to get access to blah blah blah".)

# Key notes
Raspbian X was made using a Raspberry Pi 4 2GB, so compatibility with older Pis isn't guranteed. This uses the Adapta GTK3 theme, and the Tela circle dark icon set. Both of these are not by me.

__I forgot that PulseAudio is trash. Simply run these commands in the terminal to fix the audio problems:__
```bash
sudo apt remove pulseaudio && sudo apt autoremove && sudo reboot now
```

The default username is "ubuntu", and the default password (including root) is also "ubuntu". This disk image will require a 32gb sd card, since it's backed up to a whopping 20ish GB in size. I've compressed it into a zip file for convenience.

# Download & install RaspbianX

Click on any of these links below to download a copy of RaspbianX. RaspbianX can be flashed to any 32 GB SD card, with any disk writing software. (I reccomend Rufus)

- __[Build 03.21.2020 (Latest)](https://drive.google.com/open?id=1kZAg7IHVlzSBW4GabW1Rl2GH0T_QI0By)__

# Some photos
(forgive me for using a camera, I don't have an HDMI capture device yet.)

![The login screen](https://cdn.glitch.com/2d2fd699-1471-4a63-af1a-c7b7677c8b13%2F20200322_130525.jpg?v=1584898281167)

Here is the login screen.

![The desktop](https://cdn.glitch.com/2d2fd699-1471-4a63-af1a-c7b7677c8b13%2F20200322_130605.jpg?v=1584898390637)

Take a look at the desktop here. (this won't look exactly like the image I provided above, but it's pretty much the same.)

![Sample menu](https://cdn.glitch.com/2d2fd699-1471-4a63-af1a-c7b7677c8b13%2F20200322_130614.jpg?v=1584898256214)

Just a quick sample of how the menus would look like.

# Changelog
* First build (03.21.2020) -  First initial version of RaspbianX. Not much going on here. Stable for use. Hardly any user programs at the moment, including Chromium and some basic tools for managing your Pi.

# Known bugs/issues, and what I plan on doing
* Lots of excess from the stock Raspbian Buster. I'm planning on rebuilding RaspbianX using Raspbian Buster Lite (just the OS), removing any old and unnecessary packages and programs.
* Checking for compatibility with older Pis. I don't know how well RaspbianX will perform on older Pis yet. 
* Some menus don't comply with the system theme. Trying to figure it out myself.
