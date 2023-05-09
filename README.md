CCM Over the Air update firmware Version-1.0.2
===============

### Overview

The Following repo contains upgrade firmware for CCM IFW56810-00.

From the release page, download and unzip the CCM-ota-firmware-update zip archive.

The Zip archive contains the following

-   ccm-prototype_signed_upgrade.bin
-   sig.txt (signature)

The signature is a security feature by which we will ensure that only valid images will be applied to CCM

### Information related to signature file 

-  Original hashing algorithm used: SHA-1
-  Original encryption algorithm used: RSA 

**OTA update Fails on following conditions**

-  The CCM Module is running a firmware version that is newer than the CCM OTA firmware version
-  The signature verification process fails within the CCM Module.


