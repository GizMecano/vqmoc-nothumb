# vqmoc-nothumb

## Overview

For various reasons (a responsive web design approach being one of the main), some people can search for a way to work on [OpenCart 2.x](https://github.com/opencart/opencart) by using _real images_ instead of auto-generated _thumbnails_.

A possibility [among others](http://bit.ly/1FQrjCR) is to use [vQmod](https://github.com/vqmod/vqmod) (virtual quick modifications) to retrieve these real images without changing controller content. These set of modifications include:

1. `vqmoc-nothumb.xml`: to recover main image and linked images in `category`, `product` and `search` templates
2. `vqmoc-nothumb-am.xml`: an additional file which purpose is to retrieve the same kind of data used by [Author Module](http://www.opencart.com/index.php?route=extension/extension/info&extension_id=3254) (a commercial extension for OpenCart)

## Compatibility

The latest release of these modifications have been tested with:

* [OpenCart 2.0.1.1](https://github.com/opencart/opencart/releases/tag/2.0.1.1)
* [vQmod 2.5.1](https://github.com/vqmod/vqmod/releases/tag/v2.5.1-opencart.zip) for OpenCart
* [Author Module 3.0.2](http://www.opencart.com/index.php?route=extension/extension/info&extension_id=3254)
