# Remove Symfony Polyfill
Removes Symfony polyfills from a composer project by replacing the ``symfony/polyfill-*`` libraries with no implementation.

To use add ``fivetwo/remove-symfony-polyfill`` to the ``requires`` or ``require-dev`` section of your project's composer.json file.

```json
{
    "requires": {
        "php": "~7.4.0",
        "vendor/library-requiring-symfony-polyfill": "*",
        "fivetwo/remove-symfony-polyfill": "~7.4.0"
    }
}
```

