# 4.4.9-rt17-i686-ion-v2

This custom kernel is based on linux-4.4.9 with the 4.4.9-rt17 Realtime
patchset. It is massively stripped down based upon the configuration
from the snakeoil OS kernels. Only a few devices are supported.

This release specifically supports the Nvidia ION chipset which is
found on the Zotac IONITX-A-U motherboard. It is only i686, but a
64-bit version could be created by changing the supplied configuration.
Support for USB audio devices remains, as well as support for the onboard
Atheros wireless and the ZD1201 USB wireless card. The onlboard Nvidia
ethernet works well with this kernel. LIRC has also been enabled,
and the Soundgraph iMon driver enabled to allow the iMon VFD to
work on some computer cases.

## Changelog

* v2
    * Added LIRC and Soundgraph iMon
* v1
    * Enabled NVidia ION support
    * Enabled Atheros ath9k support
    * Enabled ZyXEL ZD1201 USB WiFi support
