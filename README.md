# CI3-Startup_Template
Using the CodeIgniter 3.1.10 framework with a ready-to-use configuration

## Server Requirements

PHP version 5.6 or newer is recommended.

It should work on 5.4.8 as well, but we strongly advise you NOT to run such old versions of PHP, because of potential security and performance issues, as well as missing features.

## Installation

1. Unzip the package.
2. Upload the `CI3-Startup_Template` folders and files to your server. Normally the index.php file will be at your root.
3. Open the `application/config/config.php` file with a text editor and set your base URL:

```
// Fill in the file of your project here when you develop locally.
$host_dev = 'CI3-Startup_Template';

// Fill in the domain name here when your project is online.
// Example : www.johndoe.com
//           johndoe.com
$host_prod = 'your_domain.tld';
```

## CodeIgniter 3 Documentation

* [User guide](https://codeigniter.com/user_guide)

## Reference

* [CodeIgniter](https://github.com/bcit-ci/CodeIgniter)
* [Translations for CodeIgniter System](https://github.com/bcit-ci/codeigniter3-translations)