![banner](https://raw.githubusercontent.com/xdroid-oss/.github/55654e4a1b88977f60e2116d7cbeed17e87f450b/banner.png)

# xdroidOSS | Pixel 2 & Pixel 3

# Getting Started
---------------
To get started with the xdroidOSS sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

### Sync source ###
```bash
repo init -u https://github.com/xdroidOSS-Pixel/manifest -b thirteen
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build source ###
```
. build/envsetup.sh
lunch xdroid_$devicecodename-userdebug
make xd -j$(nproc --all)
```
### Special Credits ###
 * [**xdroidOSS**](https://github.com/xdroid-oss)

### Credits ###
 * [**AOSP**](https://android.googlesource.com)
 * [**CAF**](https://source.codeaurora.org)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**POSP**](https://github.com/PotatoProject)
 * [**StatixOS**](https://github.com/StatiXOS)
 * [**WeebProject**](https://github.com/WeebProject)
 * [**AOSPMasterVayu**](https://github.com/AOSP-Master-Vayu)
 * [**AEX**](https://github.com/AospExtended)
 * [**Evolution X**](https://github.com/Evolution-X)
 * [**PixelOS**](https://github.com/PixelOS-AOSP)

* And tons of other ROMs not mentioned above