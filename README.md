# local_manifests

# Patches:

## FOD Fixes

```bash
cd frameworks/base
wget https://raw.githubusercontent.com/project-dynamic/patch/refs/heads/main/udfps.patch && \
wget https://raw.githubusercontent.com/project-dynamic/patch/refs/heads/main/reverts.patch && \
patch -p1 <udfps.patch && \
patch -p1 <reverts.patch
cd ../..
```
