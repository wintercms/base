# Winter CMS Base

Base metapackage for Winter. This provides a handy shortcut to download all necessary requirements for Winter, including all core modules.

## Usage

If you have created a Winter installation already, you may change the following lines in your `composer.json` file:

```json
"require": {
    "php": "^8.0.2",
    "winter/storm": "dev-develop as 1.2",
    "winter/wn-system-module": "dev-develop",
    "winter/wn-backend-module": "dev-develop",
    "winter/wn-cms-module": "dev-develop",
    "laravel/framework": "^9.1",
    "wikimedia/composer-merge-plugin": "~2.1.0"
}
```

To the following:

```json
"require": {
    "winter/base": "dev-develop"
}
```

## Notes

This will not install any development dependencies or scripts. You must still source these from the standard [`composer.json`](https://github.com/wintercms/winter/blob/develop/composer.json) file in Winter and include them in your installation.
