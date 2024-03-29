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
            "url": "https://github.com/Kochava/fiftyone-php-common-api.git"
        },
]
...
"require": {
    "fiftyonedegrees/php-common-api": "dev-master"
}
...
```


## Default Branch

As of October 1, 2020, github.com uses the branch name ‘main’ when creating the initial default branch for all new repositories.  In order to minimize any customizations in our github usage and to support consistent naming conventions, we have made the decision to rename the ‘master’ branch to be called ‘main’ in all Kochava’s github repos.

For local copies of the repo, the following steps will update to the new default branch:

```
git branch -m master main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a
```
