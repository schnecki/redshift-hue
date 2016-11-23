# Redshift/Hue

This simple Python script is heavily inspired by the
[Redshift](https://github.com/jonls/redshift) project. It can change the
color temperature and the brightness of Philips Hue lamps according to the
period of the day.

## Requirements

Use `pip` to install the requirements:

    sudo pip install phue
    sudo pip install pysolar
    sudo pip install pyxdg
    sudo pip install configparser

## Configuration

The script will use the exact same configuration file as Redshift with an
additional section named `[hue]` where you need to add an option `address` that
specifies the IP address of the Hue bridge. See the sample configuration file.


