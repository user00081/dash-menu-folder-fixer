# dash-menu-folder-fixer
Assigns categories to dash folders.

To use efficently this script each of your application-you-want-to-move.desktop file must list the category that is listed in the folder you want the Application into.
In Fedora 29 systems this is usually located in: /usr/share/applications/
Anyway you may want to perform a `find / -name *.desktop -print | grep the_app_you_want_to_find` if you are unsure where the .desktop files are on your system.

## Warning
It may happen, that after you use this script, you use "Software" to make modification to folders, previous modifications will be lost.

## Sources
- [http://www.linux-commands-examples.com/gsettings](http://www.linux-commands-examples.com/gsettings)

## Credits
- [https://github.com/BenJetson/gnome-dash-fix/](https://github.com/BenJetson/gnome-dash-fix/)

## Alternatives
- [https://github.com/maoschanz/appfolders-manager-gnome-extension/](https://github.com/maoschanz/appfolders-manager-gnome-extension/)
