# Arch repository

This repository is made for my personal projects.

# Usage

Add the following lines to the end of /etc/pacman.conf:
```
[osennij-morok]
SigLevel = Optional TrustAll
Server = https://osennij-morok.github.io/arch-repo/x86_64
```

Update your repositories state:
```bash
pacman -Sy
```

To get the list of packages use
```bash
pacman -Ql osennij-morok
```
