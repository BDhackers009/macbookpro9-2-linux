## Just some fixes which i have to use when i install a new linux distro on my old MacBook Pro mid-2012

### Installing b43 drivers to enable wifi.

`sudo apt install firmware-b43-installer`

### Enabling 5Ghz wifi support

```
sudo apt install -y linux-headers-$(uname -r) && sudo apt install -y broadcom-sta-common broadcom-sta-source broadcom-sta-dkms
```
