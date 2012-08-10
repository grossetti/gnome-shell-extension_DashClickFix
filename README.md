# Gnome-Shell-Extension DashClickFix

DashClickFix "fixes" the dash's default behavior when you click on an icon. The
default is to launch the app if none is running and to switch to the current
instance if it is already running. This extension changes that to instead of
switching to it if it is already running it always launches a new instance.

Installing the extensions
-------------------------

Get it from Git using

    git clone https://github.com/grossetti/gnome-shell-extension_DashClickFix.git ~/.local/share/gnome-shell/extensions/DashClickFix@evotex.ch
    
Restart the gnome shell:

-   Press Alt+F2 and type `r` then hit **enter**.

enable it

-   using gnome-tweak-tool
-   on [extensions.gnome.org](https://extensions.gnome.org/local/)
-   or via command line using

    gnome-shell-extension-tool -e DashClickFix@evotex.ch

