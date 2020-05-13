# composer
Configuration composer.json

```JSON
{
    "name": "luizpaulogroup/groupe001",
    "description": "001",
    "minimum-stability": "stable",
    "license": "MIT",
    "authors": [
        {
            "name": "luizpaulogroup",
            "email": "your_email",
            "role": "Developer",
            "homepage": "https://github.com/luizpaulogroup"
        }
    ],
    "config": {
        "vendor-dir": "vendor"
    },
    "autoload": {
        "psr-4": {
            "Source\\": "source/"
        },
        "files": [
            "source/Config.php"
        ]
    },
    "require": {}
}

```
