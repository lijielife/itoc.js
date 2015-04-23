# itoc

It is a jQuery plugin, A toc tree generator from html document.

This repo is modify by a jquery plugin [toc](https://github.com/jgallen23/toc) .

The toc plugin document please visit [here](http://projects.jga.me/toc/) .

## Install

You can get the source from github, or install it by bower.

### Download source

    git clone https://github.com/yufeiminds/itoc.js

### Bower

    bower install itoc.js

## Usage

### Default settings

```javascript
    var defaults = {
        'selectors': 'h2, h3',
        'statistic': { H2: 0, H3: 0, H4: 0},
        'auto_num': true,
        'symbol_toc': {
            H2: ['零', '一', '二', '三', '四', '五', '六', '七', '八', '九'],
            H3: ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9'],
            H4: ['0)', '1)', '2)', '3)', '4)', '5)', '6)', '7)', '8)', '9)'],
        }
    }
```

### Init

```javascript
    $(document).ready( function() {
        $('.toc').itoc({
            /* Your custom settings */
        });
    });
```

## Contribute

1. Fork this repo.
2. Modify it.
3. Create a pull request.

happy coding...!

## Contact

**Email**

yufeiminds@gmail.com
