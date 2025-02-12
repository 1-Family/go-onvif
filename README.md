# Description
This repo is forked from https://github.com/quocson95/go-onvif, with the aim to fix & generalize a few issues.
Currently SetVideoEncoderConfiguration had been generalized to allow supporting non-default network configurations, for instance when modifying camera resolition.
- The fix has now been merged into fork source.
- This repo is kept for planned future ammendments

# Go-ONVIF

Go-ONVIF is a Go package for communicating with network camera which supports the [ONVIF](http://www.onvif.org/) specifications. ONVIF (Open Network Video Interface) is an open industry forum promoting and developing global standards for interfaces of IP-based physical security products such as network cameras. Recently, almost all network cameras support ONVIF specifications, especially network camera that made in China, which usually can bought with cheap price.



## Progress

This package is still in develoment following [guide](https://www.onvif.org/wp-content/uploads/2016/12/ONVIF_WG-APG-Application_Programmers_Guide-1.pdf) from ONVIF, with several [features](TODO.md) already available.

## License

Go-ONVIF is distributed using [MIT](http://choosealicense.com/licenses/mit/) license, which means you can use it however you want as long as you preserve copyright and license notices of this package.
