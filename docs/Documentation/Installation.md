Installation
============

The plugin should be installed using Composer.

Use the inline `require` for composer:
```
composer require ed3/search:3.*
```

or add this to your composer.json configuration:
```
{
        "require" : {
                "ed3/search": "3.*"
        }
}
```

Then you will need to load the plugin in your `config/bootstrap.php` with `Plugin::load('Search');`
