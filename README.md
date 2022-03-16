# archlinux PKGBUILD for intel-gvt-linux

## PURPOSE
Since kernel 5.12 up till now (5.16) there is an open [issue](https://github.com/intel/gvt-linux/issues/188) that may cause a Windows VM running under GVT-g to crash the host under some circunstaces.

The issue seems to be [solved](https://github.com/intel/gvt-linux/issues/188#issuecomment-1050091447) since this [commit](https://github.com/intel/gvt-linux/commit/11bd528bd71f1fd2e97a20e36b05f08602feb506) but it's currently still in staging and being monitored.

This repo contains the PKGBUILD and archlinux config files to help building the latest intel/gvt-linux/gvt-staging kernel source.

## **WARNINGS**: 

1. This kernel is **NOT** supported by **ANYONE**
2. This is a **"staging"** repository, aimed at developers and testers! (it's NOT a release kernel)
3. This **MAY CONTAIN BUGS**
4. Use **AT YOUR OWN RISK**
5. This does **NOT** build the docs, since i assume you know what you're doing

*If you're unsure what it is or why you need it, ***don't use it***.


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






