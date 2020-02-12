# Google Wallpaper Downloaders

Google provided us with some impressive wallpapers.

* [Chrome OS][Chrome OS link]
* [Google Maps][Maps link]

Now you can use them locally!

## Usage

cgiAlexis; Updated for Python 3.x, no dependencies required.

```
$ python3 chrome-os/download-wallpapers.py
$ python3 maps/download-wallpapers.py -Broken at this point
```

Wallpapers will be downloaded to relative `wallpapers` directories,
such as `chrome-os/wallpapers` and `maps/wallpapers`.

Be wary of download sizes: Chrome OS wallpapers are 200+ MB combined and Maps are 1.1+ GB.


[Chrome OS link]: https://chrome.google.com/webstore/detail/chrome-os-wallpapers/dkfibabkihblcenahmcdmfepojcejoan
[Maps link]: https://chrome.google.com/webstore/detail/earth-view-from-google-ma/bhloflhklmhfpedakmangadcdofhnnoh
