# AOSP-O FOR V500 #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/AOSP-O-V500/android_manifest -b oreo

# Sync
repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```

### Preparing to Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_v500-userdebug

# Build the code
$ mka bacon -jX
```
