# btw

X13 Yoga Gen2
=============
+ dpi scaling via `.Xresources`, add `Xft.dpi: 192` [source](https://dougie.io/linux/hidpi-retina-i3wm/)
+ firmware updates: manually edit config to point to efi partition [source](https://blog.wains.be/2021/2021-10-17-fedora-efi-fwupgrmgr/)
```
sudo vim /etc/fwupd/uefi_capsule.conf

OverrideESPMountPoint=/boot/efi
```

Misc
----
+ `iwd` weirdness, use `systemctl --now enable iwd` [source](https://superuser.com/questions/1648698/arch-linux-wlan-doesnt-work-waiting-for-iwd)
+ `dhcpcd` not happy? just dc in wd and rc
