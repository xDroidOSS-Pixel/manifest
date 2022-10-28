![banner](https://raw.githubusercontent.com/xdroidOSS-Pixel/.github/55654e4a1b88977f60e2116d7cbeed17e87f450b/banner.png)

# xdroidOSS | Pixel 2 & Pixel 3

### Sync our source ###
```bash
repo init -u https://github.com/xdroidOSS-Pixel/manifest -b thirteen
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build our source ###
```bash
. build/envsetup.sh
lunch xdroid_$devicecodename-userdebug
make xd -j$(nproc --all)
```

### Documentations ###
#### Settings
Our settings need to overlayed in device tree, you need to define your device information for our about phone section.
Reference
```bash
https://github.com/xdroid-devices/xd_device_xiaomi_lavender/commit/a94de499460e5a84aeb4cdac0c4e82ce5d88de4f
```
#### Bootanimations
Our build system need to defined about your resolution in device tree .mk e.g xdroid_lavender.mk by adding XDROID_BOOT := 1080.
We have 4 variant boot resolution ( 420, 720, 1080, 1440 )

If u have a problem with boot animation ( some device with low ram have that issue ), u didn't need to define XDROID_BOOT, it will be automatically using legacy of XD bootanimation
Reference
```bash
https://github.com/xdroid-devices/xd_device_xiaomi_lavender/commit/6f2ed2af8ee5a6165ffd231d368b03cbee5e3989
```
### Credits ###
 * [**xDroidOSS**](https://github.com/xdroid-oss)

![footer](https://github.com/xdroidOSS-Pixel/.github/raw/main/footer.png)
