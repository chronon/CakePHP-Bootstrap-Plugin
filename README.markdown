CakePHP Twitter Bootstrap Plugin
================================

Twitter Bootstrap packaged as a plugin. 

Installation:
-------------

**Using [Composer](http://getcomposer.org/)/[Packagist](https://packagist.org):**

In your project `composer.json` file:

```
{
	"require": {
		"chronon/bootstrap": "*"
	}
}
```

This will install the plugin into `Plugin/Bootstrap`.

**Using git:**

```sh
git clone git@github.com:chronon/CakePHP-Bootstrap-Plugin.git APP/Plugin/Bootstrap
```

Usage:
-----

In your app's `Config/bootstrap.php`:

```php
<?php
CakePlugin::loadAll(array(
	'Bootstrap'
));
```

In your layout:

```php
<?php
echo $this->Html->css(array(
	'Bootstrap.bootstrap.min.css',
	'Bootstrap.bootstrap-responsive.min.css'
)); 
```

```php
<?php
echo $this->Html->script(array(
	'//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js',
	'Bootstrap.bootstrap.min.js'
));
```
