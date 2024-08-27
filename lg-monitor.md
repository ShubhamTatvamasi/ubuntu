# LG Monitor

Simple GNOME extension to control displays' brightness via DDC.

## Preparation

1. Install `ddcutil`: 

```shell
sudo apt install ddcutil
```

2. Set I2C permissions for non-root users: 

```shell
sudo adduser $USER i2c
sudo /bin/sh -c 'echo i2c-dev >> /etc/modules'
```
A reboot is needed.

[https://github.com/daitj/gnome-display-brightness-ddcutil](https://extensions.gnome.org/extension/2645/brightness-control-using-ddcutil/)
