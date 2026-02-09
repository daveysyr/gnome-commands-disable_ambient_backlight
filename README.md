# gnome-commands-disable_ambient_backlight

## This is a location to store and circulate the two commands for switching the auto ambient backlight on and off within the Gnome desktop.

One of the issues that I have with my Dell Latitude 7350 2-in-1 detachable, is that the ambient backlight is constantly adjusting the screen brightness and not only do I find that to be really distracting, but it was distracting other people in the same room as me.

There are two simple commands that you can run in the terminal, one to switch off the auto screen brightness and one to switch it back on. I intially wrote this as a Gnome Extension, because I know that many new users will be a bit wary of the terminal. Unfortunately, the guys at Gnome didn't like that I was using extensions to make the UI do things that they'd chosen to prevent it doing. That's a bit unfortunate, because I was just trying to help others. Gnome should probably surface this as a toggle, but well...you know what Gnome are like for trying to keep the interface and options clean.

Having had the toggle function for some time now, I personally feel that most people will probably be either an "auto brightness on" or "auto brightness off" type of person.  I doubt that once you've set things to either on or off, you'll need to change the settings again.

So...how to use? All you have to do is just paste the relevant command(s) into your terminal and hit enter.

Changes will stick until you run the alternative command to switch the auto backlight back on/off.  


### Show current state

gsettings get org.gnome.settings-daemon.plugins.power ambient-enabled


### Disable ambient backlight

gsettings set org.gnome.settings-daemon.plugins.power ambient-enabled false


### Enable ambient backlight

gsettings set org.gnome.settings-daemon.plugins.power ambient-enabled true


It's as simple as that. Run a command to switch things off and another to switch things back on again.  Enjoy!!
