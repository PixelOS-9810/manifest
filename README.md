# PixelOS #

### Initialize local repository ###
```
repo init -u https://github.com/PixelOS-9810/manifest -b twelve
```

### Sync ###
```
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```

### Build ###

```
$ . build/envsetup.sh
$ lunch aosp_$device-user
$ mka bacon -j$(nproc --all)
```
