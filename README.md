# imagenet-download
Python scripts to download imagenet images and pre-proccess them

example usage:

 ./imagenetDownloader.py  n03489162 ../dataset --humanreadable -F --images=50 --minsize=7000 -j10
In order to download 50 images from any category under any subtree (-F) of the handtools (n03489162), running 10 threads in parallel, and only downloading images larger than 7kB.
