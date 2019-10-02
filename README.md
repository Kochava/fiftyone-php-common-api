# 51 Degrees / PHP / Common API

A mirrored version of 51 Degree's `php/common-api` with an updated `composer.json`.

## Update when 51 Degrees releases

Run `update.sh` when 51 Degrees releases a new version

```
$ ./update.sh v3.2.20.4
```

## Add to composer

Update your projects `composer.json` with a new `repositories` entry and require
the needed version.

```
"repositories": [
        {
            "type": "git",
            "url": "git@github.com/Kochava/fiftyone-php-common-api.git"
        },
]
...
"require": {
    "fiftyonedegrees/php-common-api": "dev-master"
}
...
```
