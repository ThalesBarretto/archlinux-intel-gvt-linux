# archlinux PKGBUILD for intel-gvt-linux

##**WARNINGS**: 

1. This kernel is **NOT** supported by **ANYONE**
2. This is a **"staging"** repository, aimed at developers and testers! (it's NOT a release kernel)
3. This **MAY CONTAIN BUGS**
4. Use **AT YOUR OWN RISK**
5. This does **NOT** build the docs, since i assume you know what you're doing

*If you're unsure what it is or why you need it, ***don't use it***.

This repo contains the PKGBUILD and archlinux config files to ease building 
the latest intel/gvt-linux/gvt-staging kernel source.

To use this repo:

1. clone it:
```bash
/... $> git clone 
```
2. cd into the directory
```bash
 /... $> cd archlinux-intel-gvt-linux
```
3. explore your own options, check your /etc/makepkg.conf (optional)
4. use makepkg 
```bash
.../archlinux-intel-gvt-linux $> makepkg --install
```






