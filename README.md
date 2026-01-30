# Clone Source:

```bash
git clone -b 16 https://github.com/neophyteprjkt/local_manifest --depth=1 .repo/local_manifests
```
# Then to sync up:
```
repo sync -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune
