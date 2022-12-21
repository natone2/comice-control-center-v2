# comice-control-center-v2
A little modification for Debian distros.

I have modified the code to work on distros related to debian, more specifically I have tested it in Kali Linux.


## Screenshot
![Screenshot](https://raw.githubusercontent.com/natone2/comice-control-center-v2/main/screenshots/screenshot.png)


## Compilation

1. Install build dependencies:
```bash
sudo apt install python3 python3-dbus util-linux gsettings-desktop-schemas wireless-tools alsa-utils
```
2. Install python3 (pip) dependencies:
```bash
sudo pip3 install -r requirements.txt
```
3. Run `comice-control-center` standalone:
```bash
./comice-control-center
```

## Changelog
**Version 0.0.2**
* Modified version
* BT Error solved
* Reimplemented widgets for connections, sound volume and monitor brightness
* Reusable functions

this is a revision of the GPLv3-licensed https://github.com/libredeb/comice-control-center code.
