## Composer.json

```json
{
    "name": "private-modulename",
    "description": "ZF2 demo",
    "type": "zf-module",
    "homepage": "https://private-repository",
    "authors": [
        {
            "name": "QuangTM",
            "email": "quangtm@hdviet.com"
        }
    ],
    "require": {
        "php": "~5.4",
        "zendframework/zendframework" : "~2.2"
    },
    "autoload": {
        "psr-0": {
            "Backend": "src/"
        },
        "classmap": [
            "./Module.php"
        ]
    }
}

```