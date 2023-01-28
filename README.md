## Recovery Device Tree for the Samsung W2019 (Snapdragon)

## How-to compile it:

```sh
chmod -x ./device/samsung/lykanltechn/mkbootimg
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_lykanltechn-eng
make recoveryimage
```


