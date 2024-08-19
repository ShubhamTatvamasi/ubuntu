# ubuntu

Open a Terminal window and type:
```bash
sudo visudo
```

In the bottom of the file, add the following line:
```bash
$USER ALL=(ALL) NOPASSWD: ALL
```

Install the Gnome desktop on Ubuntu server Edition enter:
```bash
# This will give you most of the stock Ubuntu Desktop, minus some applications:
sudo apt install ubuntu-desktop

# This will give you the complete stock Ubuntu Desktop with all applications installed from the Desktop image:
sudo apt install ubuntu-desktop --install-recommends
```

How to Change Lid Close Behavior in Ubuntu 20.04

https://ubuntuhandbook.org/index.php/2020/05/lid-close-behavior-ubuntu-20-04/

