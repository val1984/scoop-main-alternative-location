# Scoop main packages with alternatives locations

[![Tests](https://github.com/val1984/scoop-main-alternative-location/actions/workflows/ci.yml/badge.svg)](https://github.com/val1984/scoop-main-alternative-location/actions/workflows/ci.yml) [![Excavator](https://github.com/val1984/scoop-main-alternative-location/actions/workflows/excavator.yml/badge.svg)](https://github.com/val1984/scoop-main-alternative-location/actions/workflows/excavator.yml)

Purpose of this bucket
----------------------

This bucket contains very few manifests and is not intended to be used as a regular bucket. If `scoop` is working properly for you, you shouldn't use of any of the manifests hosted on this bucket.

Theses manifests contain alternate download locations from the official mirrors to try to work around inconsistent corporate blocking rules.

These get auto-updated with Excavator GitHub action and will be displayed on `scoop status` whenever an update is available.

How do I install these manifests?
---------------------------------

You should navigate to the [bucket/](bucket) folder, click on the package manifest you want and copy the raw link to use with `scoop install`:
```
scoop install https://github.com/val1984/scoop-main-alternative-location/raw/main/bucket/7zip.json
scoop install https://github.com/val1984/scoop-main-alternative-location/raw/main/bucket/git.json
scoop install https://github.com/val1984/scoop-main-alternative-location/raw/main/bucket/notable.json
scoop install https://github.com/val1984/scoop-main-alternative-location/raw/main/bucket/wslgit.json
```
