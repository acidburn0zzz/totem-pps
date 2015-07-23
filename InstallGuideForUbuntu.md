totem-pps is available in postis25's ppa.

# 1. Add one of ppa following sources #
## PPA for lucid ##
```

deb http://ppa.launchpad.net/portis25/ppa/ubuntu lucid main
deb-src http://ppa.launchpad.net/portis25/ppa/ubuntu lucid main
```
## PPA for karmic ##
```
deb http://ppa.launchpad.net/portis25/cnav/ubuntu karmic main
deb-src http://ppa.launchpad.net/portis25/cnav/ubuntu karmic main
```

# 2. Install totem-pps #
```
sudo apt-key adv --recv-keys --keyserver keyserver.ubuntu.com 27F5B2C1B3EAC8D9
sudo apt-get update
sudo apt-get install totem-pps
```