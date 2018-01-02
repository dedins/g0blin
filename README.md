# g0blin-apt

(WIP) jailbreak for iOS 10.3.x on A7-A9 devices

v0rtex + yalu102 + apt

## what works
- tfp0
- kernel r/w access
- remount / as r/w
- amfi patched
- Dropbear: automatically starts an ssh server listening on port 2222
- Cydia Substrate
- Cydia (partially: usefull to add/remove sources or browse packages info)
- apt-get and dpkg to install packages

## what doesn't work
- Cydia installation

## How to install packages
### To update sources
apt-get update

###To search packages
cydia_search <package_name>

### To install something
cydia_install <package_name>

### To remove something 
cydia_remove <package_name>

### To reload data (uicache + respring)
cydia_reload

creds: qwertyoruiopz, Sizuga, Xenu, Saurik, Sticktron 
