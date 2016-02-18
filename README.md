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

## Installation

After having [installed integration of vQmod for OpenCart](https://github.com/vqmod/vqmod/wiki/Installing-vQmod-on-OpenCart), simply copy the `.xml` files in the `vqmod\xml` folder.

## Licence

vqmoc-nothumb: custom modifications to display real images and no thumbnails in OpenCart 2.x

---

Copyright © 2015-2016 P. Mergey

This program is free software: you can redistribute it and/or modify it under the terms of the [GNU General Public License](LICENSE) as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU General Public License](LICENSE) for more details.

You should have received a copy of the [GNU General Public License](LICENSE) along with this program. If not, see [this page](http://www.gnu.org/licenses/gpl-3.0.txt).
