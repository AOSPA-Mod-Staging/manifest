# OctaviOS Android Manifest #

### Initialize OctaviOS ###

**Initialize full repository (useful for developers)**
```
repo init -u https://github.com/OSS-Random/android_manifest -b sixteen --git-lfs
```

**If you want to save space, use this instead**
```
repo init -u https://github.com/OSS-Random/android_manifest -b sixteen --git-lfs --depth 1
```

### Sync Sauce ###
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch
```

### Strike the Octave ###
```
. build/envsetup.sh

brunch device
```

## Now Build and Enjoy! ##
