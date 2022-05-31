# Remove Symfony Polyfill
Removes Symfony polyfills from a composer project by replacing the ``symfony/polyfill-*`` libraries with no implementation.

To use add ``fivetwo/remove-symfony-polyfill`` to the ``require`` or ``require-dev`` section of your project's composer.json file.

```json
{
    "require": {
        "php": "~8.1.0",
        "vendor/library-requiring-symfony-polyfill": "*",
        "fivetwo/remove-symfony-polyfill": "~8.1.0"
    }
}
```

