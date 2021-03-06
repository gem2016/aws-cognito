pmill/aws-cognito
=================

Introduction
------------

This library contains a PHP client for AWS Cognito user pools.

Requirements
------------

This library package requires PHP 7.0 or later

Installation
------------

### Installing via Composer

The recommended way to install is through
[Composer](http://getcomposer.org).

```bash
# Install Composer
curl -sS https://getcomposer.org/installer | php
```

Next, run the Composer command to install the latest version:

```bash
composer.phar require pmill/aws-cognito
```

Usage
--------

There are example usage scripts in the `examples/` folder, copy `examples/config.example.php` to `examples/config.php` 
before running them.


Version History
---------------

0.1.3 (12/11/2017)

*   Returned generated cognito username when registering

0.1.2 (20/05/2017)

*   Added method to refresh authentication tokens

0.1.1 (30/04/2017)

*   Returned username when verifying access tokens

0.1.0 (28/04/2017)

*   First public release of aws-cognito


Copyright
---------

pmill/aws-cognito
Copyright (c) 2017 pmill (dev.pmill@gmail.com) 
All rights reserved.
