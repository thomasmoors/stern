# Stern CMS

[![Latest Version on Packagist](https://img.shields.io/packagist/v/spatie/:package_name.svg?style=flat-square)](https://packagist.org/packages/spatie/:package_name)
[![GitHub Tests Action Status](https://img.shields.io/github/workflow/status/spatie/:package_name/run-tests?label=tests)](https://github.com/spatie/:package_name/actions?query=workflow%3Arun-tests+branch%3Amaster)
[![Total Downloads](https://img.shields.io/packagist/dt/spatie/:package_name.svg?style=flat-square)](https://packagist.org/packages/spatie/:package_name)

**Note:** Replace ```:author_name``` ```:author_username``` ```:author_email``` ```:package_name``` ```:package_description``` with their correct values in [README.md](README.md), [CHANGELOG.md](CHANGELOG.md), [CONTRIBUTING.md](CONTRIBUTING.md), [LICENSE.md](LICENSE.md) and [composer.json](composer.json) files, then delete this line. You can also run `configure-skeleton.sh` to do this automatically.

This is where your description should go. Limit it to a paragraph or two. Consider adding a small example.

## Installation

You can install the package via composer:

```bash
composer require spatie/package-skeleton-laravel
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --provider="Spatie\Skeleton\SkeletonServiceProvider" --tag="migrations"
php artisan migrate
```

You can publish the config file with:
```bash
php artisan vendor:publish --provider="Spatie\Skeleton\SkeletonServiceProvider" --tag="config"
```

This is the contents of the published config file:

```php
return [
];
```

## Usage

``` php
$skeleton = new Spatie\Skeleton();
echo $skeleton->echoPhrase('Hello, Spatie!');
```

## Testing

``` bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email 16e08b42-86aa-483b-ab60-3d308587c043@thomasmoors.anonaddy.com instead of using the issue tracker.

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

## Naming
Stern means both "serious and unrelenting" and "the back part of a ship or boat". Both apply, we strive to make something robust and worthy of serving websites that need a certain level of maturity in their CMS. And I'd like to see a CMS as the backside of things, be it the back part of a boat, the dark side of the moon or the hidden part of the iceberg.

## Goals
 - [ ] Simple to use without taking away the ability to do advanced stuff
 - [ ] Extensible
 - [ ] With best practises in mind, both in coding as in running a website
 - [ ] Event sourcing driven, so you never lose any content
 - [ ] Community driven when ready for production: decisions will be made through polls
 - [ ] Convenience like for example the ability to translate assets automatically by sending it to a translation agency through an API
 - [ ] Extensive documentation that is easy to understand. A great example is the Laravel documentation
 - [ ] Previewing layouts with dummy data like images from [Unsplash](https://source.unsplash.com/)
 
 ## No need to reinvent the wheel
 We try to be smart and borrow some packages from other developers
 - [Gutenberg](https://wordpress.org/gutenberg/) (Probably through [Laraberg](https://github.com/VanOns/laraberg))
 - [CoreUI](https://coreui.io/)
 - [Event sourcing](https://github.com/spatie/laravel-event-sourcing)
 - [Roles and permissions](https://github.com/spatie/laravel-permission)
 - [Media management](https://github.com/ctf0/Laravel-Media-Manager)
 
 ## Let's talk money
 ### Taking
 You never have to pay for this CMS directly or for it's plugins. Of course plugin developers are free to require an account for their external service and charge money. It will be mandatory to label your plugin as such in that case. However you never need to pay to download the source code.
 
 The way we might want to earn some money is by user being able to donate towards specific goals/features. This way we could spent more time towards this project, hire other developers or auditors so this can truly become the greatest CMS there is. For now this won't happen, because we first need a stable working application. Also we do like to offer the ability to sell templates, but might take a small share of the profits. Max 5%.
 
 ### Giving
Because we use a lot of other developers work, we'd like to give something back. At the moment I'm not sure what would be fair, at least 10% I'd think.
