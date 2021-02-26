# Install Visual Studio Code on Ubuntu 20.04 LTS

We will install Visual Studio Code using the SNAP package manager

    $ sudo snap install --classic code

Note: If **snap** is not available on your installation, you can check the *Installilng snapd guide* at this location https://snapcraft.io/docs/installing-snapd

## Alternative installations

You can read the source for the the Visual Studio Code installation for Linux at this location https://code.visualstudio.com/docs/setup/linux

## Using Visual Studio Code as default text Editor

### xdg-open

Run this command from the terminal

    $ xdg-mime default code.desktop text/plain


Thats All!!!

