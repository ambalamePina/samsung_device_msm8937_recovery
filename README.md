## Recovery Device Tree for the Samsung Galaxy M01 (Snapdragon)

## How-to compile it:

```sh
repo init --depth=1 -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-10.0
repo sync
git clone https://github.com/horoid/samsung_device_msm8937_recovery.git device/samsung/m01q
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_m01q-eng
make recoveryimage
```
Bugs
Encryption , 
Fastbootd
