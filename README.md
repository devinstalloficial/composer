# composer
Configuration composer.json

```JSON
{
    "name": "your_name",
    "description": "description",
    "minimum-stability": "stable",
    "license": "MIT",
    "authors": [
        {
            "name": "name",
            "email": "email",
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
