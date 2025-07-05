1. Install `bcmwl-kernel-source` package

```
sudo apt-get update
sudo apt-get --reinstall install bcmwl-kernel-source
```
2. To test the driver without the need for a restart

```
sudo modprobe -r b43 ssb wl brcmfmac brcmsmac bcma
sudo modprobe wl
```