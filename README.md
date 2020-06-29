# ImageNet URL Downloader

Python utility script for downloading subtrees of ImageNet using the URLs provided by the ImageNet API.

This repository is a fork of https://github.com/itf/imagenet-download and includes some upgrades to allow for more robust downloads:

- [x] Image downloads don't fail if the URL (or rather IRI) includes non-ASCII characters
- [ ] Retry getting list of URLs if the ImageNet API does not respond temporarily (this happens very frequently as of now!)
- [ ] Resume downloads


__Please note__ that this project is currently WIP (as of June 2019) and is expected to receive major updates during the next days!
