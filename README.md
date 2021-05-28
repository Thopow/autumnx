# The AutumnX-Project

This project is a spin on the Xfce4 desktop and the Herbstluftwm window manager to create a modern and work-flow oriented Desktop Environment. 

## Basic motivation
I fall in love with the work-flow of a tiling window manager but to set it up and make it functional is a lot of work. And ask for some level of insider knowledge of an operation system not everyone have. 
### Desktop Tools
So I decided to create this project and use a lite wight and flexible desktop environment like Xfce4 and bend it to my like. At this doing it showed that it is better to use as main driver the window manager and run on to the Xfce tools. Also we need to use some third party tools to replace some to avoid conflicts.
### Window Manager
My choice for the Herbstluft Window Manager (HLWM) is based of its solid code base and the fact that it is possibly the easiest to configure with a first class "man page".

## Basic Description
I used a Fedora34 Xfce installation as the base for this project but I guess it will work with any kind of Distro with Xfce4 desktop. On top of this I installed herbstluftwm, picom, rofi and nitrogen. Which I found in my standard Repos. 

### Xfce4 Setup 
Here we need to edit the Session and Startup cinfig. Under "Current Session" we need to remove the "Xfwm" and the "Xfce-Desktop" then "Save Session". And under the xfce keyboard settings we need to remove all keybindings.

Now we have to add the HLWM autostart file in ~/.config/herbstluftwm/ [(You can download it from here)](https://github.com/Thopow/autumnx) or create your own by copy the default one from /etc/xdg/herbstluftwm/autostart to ~/.config/herbstluftwm/ .

Now we can log out, change the desktop environment to herbstluftwm and log in into our new "AutumnX" desktop.

