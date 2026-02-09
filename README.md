# gnome-commands-disable_ambient_backlight

## This is a location to store and circulate the two commands for switching the auto ambient backlight on and off within the Gnome desktop.


One of the issues that I have with my Dell Latitude 7350 2-in-1 detachable, is that the ambient backlight is constantly adjusting the screen brightness and not only do I find that to be really distracting, but it was distracting other people in the same room as me.

So...how to use? All you have to do is just paste the relevant command(s) into y

Changes will stick until you run the alternative command to switch the auto backlight back on/off.  


### Show current state

gsettings get org.gnome.settings-daemon.plugins.power ambient-enabled


### Disable ambient backlight

gsettings set org.gnome.settings-daemon.plugins.power ambient-enabled false


### Enable ambient backlight

gsettings set org.gnome.settings-daemon.plugins.power ambient-enabled true


It's as simple as that. Run the relevant command to switch things off and the other to switch things back on again. The status check is just for your peace of mind.

I hope this helps. Enjoy!!
