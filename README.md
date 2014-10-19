# wkhtmltopdf for Ubuntu 14.04 (trusty)

[All the binaries for Ubuntu 14.04 (trusty) from http://wkhtmltopdf.org/downloads.html](http://wkhtmltopdf.org/downloads.html)

## Install

1. Install Composer:

    ```    
    curl -s https://getcomposer.org/installer | php
    ```
    
2. Add to your `composer.json` file:

    ```js
    {
        "require": {
            "profburial/wkhtmltopdf-binaries-trusty": "1.0"
        }
    }
    ```

3. All the binaries are symlinked to the following paths:

```
vendor/bin/wkhtmltoimage-linux-trusty-amd64

vendor/bin/wkhtmltoimage-linux-trusty-i386

vendor/bin/wkhtmltopdf-linux-trusty-amd64

vendor/bin/wkhtmltopdf-linux-trusty-i386
```

Enjoy the bin files!