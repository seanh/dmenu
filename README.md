My dmenu Scripts
================

[dmenu](https://tools.suckless.org/dmenu/) themed to fit in with GNOME's top bar.
Menu items are read from a [`menu.txt` file](menu.txt) and the selected
menu item is executed as a command.

Installation
------------

### Ubuntu 20.04

Enable Ubuntu's "Community-maintained free and open-source
software (universe)" option in the **Software & Updates** app,
then:

```terminal
sudo apt install --yes git suckless-tools
git clone 'https://github.com/seanh/dmenu.git' ~/.dmenu
```

Then run:

```terminal
~/.dmenu/dmenu-run-gnome
```
