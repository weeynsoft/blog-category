# Weeyn Blog Category Module
Weeyn blog category module

![Packagist PHP Version](https://img.shields.io/packagist/dependency-v/weeynsoft/blog-category/php)
![Packagist Version](https://img.shields.io/packagist/v/weeynsoft/blog-category)
![Packagist Downloads](https://img.shields.io/packagist/dt/weeynsoft/blog-category?label=download)
![GitHub](https://img.shields.io/github/license/weeynsoft/blog-category)


This is the standalone blog category module of the [Weeyn](https://weeyn.com).

## Installation

(As Standalone Component)

1. `composer require weeynsoft/blog-category`
2. `php artisan vendor:publish --provider="Konekt\Concord\ConcordServiceProvider"`
3. Add `Weeyn\BlogCategory\Providers\ModuleServiceProvider::class` to modules in `config/concord.php`
4. `php artisan migrate`

## Usage

See the [Weeyn Category Module Documentation](https://weeyn.com/docs/master/blog-category) for more details. 

## About Us

Weeyn development is led by the core team.