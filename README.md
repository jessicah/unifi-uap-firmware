# unifi-uap-firmware

Firmware for the original Unifi UAP

Unifi make it very difficult to search for the firmware, so here are the links to firmware:

- https://dl.ubnt.com/unifi/firmware/BZ2/3.7.58.6385/BZ.ar7240.v3.7.58.6385.170508.0942.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/3.8.3.6587/BZ.ar7240.v3.8.3.6587.170609.0748.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/3.8.6.6650/BZ.ar7240.v3.8.6.6650.170712.2142.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/3.8.14.6780/BZ.ar7240.v3.8.14.6780.170915.2224.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/3.9.3.7537/BZ.ar7240.v3.9.3.7537.171013.1042.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/3.9.15.8011/BZ.ar7240.v3.9.15.8011.171208.1655.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/3.9.19.8123/BZ.ar7240.v3.9.19.8123.180104.1438.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/3.9.21.8191/BZ.ar7240.v3.9.21.8191.180119.2342.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/3.9.27.8537/BZ.ar7240.v3.9.27.8537.180317.1223.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/3.9.54.9373/BZ.ar7240.v3.9.54.9373.180913.2356.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/4.0.9.9636/BZ.ar7240.v4.0.9.9636.181128.2215.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/4.0.10.9653/BZ.ar7240.v4.0.10.9653.181205.1311.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/4.0.14.9736/BZ.ar7240.v4.0.14.9736.181224.1724.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/4.0.15.9872/BZ.ar7240.v4.0.15.9872.181229.0259.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/4.0.42.10433/BZ.ar7240.v4.0.42.10433.190518.0923.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/4.0.54.10625/BZ.ar7240.v4.0.54.10625.190801.1544.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/4.0.66.10832/BZ.ar7240.v4.0.66.10832.191023.1948.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/4.0.69.10871/BZ.ar7240.v4.0.69.10871.191109.0532.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/4.0.80.10875/BZ.ar7240.v4.0.80.10875.200111.2335.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/4.3.13.11253/BZ.ar7240.v4.3.13.11253.200430.1420.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/4.3.20.11298/BZ.ar7240.v4.3.20.11298.200704.0747.bin
- https://dl.ubnt.com/unifi/firmware/BZ2/4.3.21.11325/BZ.ar7240.v4.3.21.11325.200922.1739.bin
- https://dl.ui.com/unifi/firmware/BZ2/4.3.28.11361/BZ.ar7240.v4.3.28.11361.210128.2309.bin

Host on a webserver, and then ssh in (ubnt/ubnt) and `upgrade http://.../path/to.bin`.

Certain firmware cannot be upgraded from a too old firmware, I just went through every single
version, and then Unifi Controller could finally adopt the UAP.

Attempting to adopt and upgrade the original UAP on a too old firmware would otherwise get
stuck trying to update. Step-wise upgrading of firmware resulted in Unifi Controller seeing
it as fully upgraded, allowing to adopt without further upgrading.
