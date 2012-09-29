CakePHP Twitter Bootstrap Plugin
================================

Twitter Bootstrap packaged as a plugin. 

Installation:
-------------

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
	'Bootstrap.bootstrap-responsive.min.css
)); 
```

```php
<?php
echo $this->Html->script(array(
	'//ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js',
	'Bootstrap.bootstrap.min.js'
));
```
