# CCM Over the air update firmware 
===============

## Overview

This repository contains the updated firmware for the CCM IFW56810-00 Module.

To perform the update, please download and extract the CCM-ota-firmware-update zip archive from the release page.

Inside the zip archive, you will find the following files:

-  ccm-prototype_signed_upgrade.bin
-  sig.txt (signature)

The signature serves as a security measure to ensure that only valid images are applied to the CCM.

## Information related to signature file 

-  Original hashing algorithm used: SHA-1
-  Original encryption algorithm used: RSA 

## OTA update Fails on following conditions**

-  The CCM Module is running a firmware version that is newer than the CCM OTA firmware version.
-  The signature verification process fails within the CCM Module.

---
© Cypress Semiconductor Corporation (an Infineon company), 2023
