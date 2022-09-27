# kernel_cache_downloader
A python script for download kernelcache without download ipsw.
Can search for development kernelcache :)
Can you filter for versions or models
Thanks to [m1stadev's ios beta api](https://github.com/m1stadev/ios-beta-api) and [tihmstar's partialZipBrowser](https://github.com/tihmstar/partialZipBrowser) 

## Requirements
* An Internet connection
* PyPI dependencies:
    * python3 -m pip install -r requirements.tx

## Usage
* -v "15.0 16" => query only iOS versions contains '15.0' or '16'
* -m "iPhone11,2 iPhone8,1" => query only iOS models contains 'Phone11,2' or 'iPhone8,1'
* -b 1 => query beta ipsw
* -d 1 => search only for develoment kernelcache
