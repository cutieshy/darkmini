# darkmini

## Dark theme for rEFInd

I reccomend creating a `/boot/EFI/refind/theme` folder and then moving the contents of this repo excluding the `README.md`. 
After that it's as simple as adding ```include theme/theme.conf``` anywhere inside your refind.conf.

```
sudo su
mkdir /boot/EFI/refind/theme
cd /boot/EFI/refind/theme
cp "this repo" ./
```