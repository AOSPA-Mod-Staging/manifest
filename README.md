# Paranoid Android (AOSPA) MOD #

### Initialize Paranoid Android Mod ###
```
repo init -u https://github.com/AOSPA-Mod/manifest -b mod --depth 1
```

### Sync Sauce ###
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune
```

### Cook AOSPA ###
```
./rom-build.sh device
```

## Now Build and Enjoy! ##
