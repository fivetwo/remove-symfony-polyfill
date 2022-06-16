# Remove Symfony Polyfill
This library removes Symfony polyfills from a composer project by replacing the `symfony/polyfill-*` libraries with no implementation.

To install, add `fivetwo/remove-symfony-polyfill` to the `require` or `require-dev` section of your project's composer.json file.

```json
{
    "require": {
        "fivetwo/remove-symfony-polyfill": "~7.2.0"
    }
}
```

Alternatively, install from the command line.

```shell
composer require "fivetwo/remove-symfony-polyfill"
```
