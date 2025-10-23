# Pixel Experience #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/Khaikate/PEmanifest -b ten

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_device-userdebug

# Build the code
$ mka bacon