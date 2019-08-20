# Notes to Self

This document is for me to take note of the steps I've taken to get void working the way I want it to. In other words, what follows is a step by step process of all the packages I downloaded and if/how I configured them
- After the initial install I downloaded NetworkManager with `sudo xbps-install -S NetworkManager` then I disabled the runit service for `wpa_supplicant` and `dhcpcd`
- Install `git` for gitting and `make` for making
- Installing an X.org server
  - Packages I used include `xorg`
