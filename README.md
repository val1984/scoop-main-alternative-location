# Scoop main packages with alternatives locations

[![Tests](https://github.com/val1984/scoop-main-alternative-location/actions/workflows/ci.yml/badge.svg)](https://github.com/val1984/scoop-main-alternative-location/actions/workflows/ci.yml) [![Excavator](https://github.com/val1984/scoop-main-alternative-location/actions/workflows/excavator.yml/badge.svg)](https://github.com/val1984/scoop-main-alternative-location/actions/workflows/excavator.yml)

How do I install these manifests?
---------------------------------

You should navigate to the [bucket/](bucket) folder, click on the package manifest you want and copy the raw link to use with `scoop install`:
```
scoop install https://github.com/val1984/scoop-main-alternative-location/raw/main/bucket/7zip.json
scoop install https://github.com/val1984/scoop-main-alternative-location/raw/main/bucket/git.json
scoop install https://github.com/val1984/scoop-main-alternative-location/raw/main/bucket/notable.json
```

These packages auto-update with Excavator GitHub action and will be displayed on `scoop status` when an update is available.
