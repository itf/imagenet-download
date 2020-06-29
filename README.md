# ImageNet URL Downloader

Python utility script for downloading subtrees of ImageNet using the URLs provided by the ImageNet API.

example usage:

 ./imagenetDownloader.py  n03489162 ../dataset --humanreadable -F --images=50 --minsize=7000 -j10

In order to download 50 images from any category under any subtree (-F) of the handtools (n03489162), running 10 threads in parallel, and only downloading images larger than 7kB.

- [x] Image downloads don't fail if the URL (or rather IRI) includes non-ASCII characters
- [ ] Retry getting list of URLs if the ImageNet API does not respond temporarily (this happens very frequently as of now!)
- [ ] Resume downloads


__Please note__ that this project is currently WIP (as of June 2019) and is expected to receive major updates during the next days!
