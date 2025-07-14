## [OneShot](https://github.com/siper86/Oneshot_Termux_installer) installer for [Termux](https://termux.com/)
### Setup
```
curl -sSf https://github.com/siper86/Oneshot_Termux_installer/master/installer.sh | bash
```
### Run
Disable Wi-Fi in the system settings and run:
```
sudo python OneShot/oneshot.py -i wlan0 -K
```
### How to update OneShot
To check for updates and update, run the following command:
```
(cd OneShot && git pull)
```
