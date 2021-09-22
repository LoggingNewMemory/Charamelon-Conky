# Charamelon-Conky
Charamelon is Conky Theme based on LinuxScoop Conky
Youtube: https://www.youtube.com/channel/UCNnUnr4gwyNmzx_Bbzvt29g

You May Modify The Files For Your Needs

[Preview On Desktop]

![WhatsApp Image 2021-09-22 at 10 57 25](https://user-images.githubusercontent.com/83739103/134283553-c13762bf-0457-466d-b2cf-5791860d63bd.jpeg)

[Conky Only]

![WhatsApp Image 2021-09-22 at 10 58 23](https://user-images.githubusercontent.com/83739103/134283777-c3dc4164-50b3-40ba-bcd8-8b9265107800.jpeg)

[Conky + Audacious]

![WhatsApp Image 2021-09-22 at 10 59 35](https://user-images.githubusercontent.com/83739103/134283812-3e1a967e-a81f-4cc5-be3f-9e1e1dfb68b8.jpeg)

Setup Audacious:

1. Go to Services > Plugins > General
2. Enable the "Song Change" Plugin
3. set the "Commands to run when starting a new song" to cp /tmp/audacious-temp* /tmp/audacious-cover.jpg
4. set the "Commands to run at the end of a song" to %n

Installing conky:

Ubuntu : 

sudo apt install conky

Fedora :

sudo dnf install conky

openSUSE :

sudo zypper install conky

Arch linux:

sudo pacman -S conky

Installing the Conky Theme:

just copy all the files to /.config/conky

Note: if the conky folder doesn't exist just make the folder 

Pardon Me For My Bad English
