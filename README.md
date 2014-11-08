yii2-krajee-base
================
This is a base library with set of foundation classes and components used by all [Yii2 extensions by Krajee](http://demos.krajee.com). One can use this base library during creation of one's own extensions if needed.

> NOTE: This extension depends on the [yiisoft/yii2-bootstrap](https://github.com/yiisoft/yii2/tree/master/extensions/bootstrap) extension. Check the [composer.json](https://github.com/kartik-v/yii2-krajee-base/blob/master/composer.json) for this extension's requirements and dependencies. 

## Why this extension?
 
To ensure a leaner code base / foundation component for use in all Krajee extensions (e.g. yii2-widgets, yii2-grid, yii2-dynagrid etc.). This should allow most developers to plug and play components only they need, without needing the complete suite of widgets. For example, this mitigates [this issue](https://github.com/kartik-v/yii2-grid/issues/123). 

## Extension Classes

### [Widget](https://github.com/kartik-v/yii2-krajee-base/blob/master/Widget.php)
Extends [Yii Widget](https://github.com/yiisoft/yii2/blob/master/framework/base/Widget.php) class for Krajee's Yii2 widgets and usage with bootstrap CSS framework. 

### [InputWidget](https://github.com/kartik-v/yii2-krajee-base/blob/master/InputWidget.php)
Extends [Yii InputWidget](https://github.com/yiisoft/yii2/blob/master/framework/widgets/InputWidget.php) class for Krajee's Yii2 widgets and usage with bootstrap CSS framework. 
	
### [AssetBundle](https://github.com/kartik-v/yii2-krajee-base/blob/master/AssetBundle.php)
Extends [Yii AssetBundle](https://github.com/yiisoft/yii2/blob/master/framework/web/AssetBundle.php) class for Krajee's Yii2 widgets with enhancements for using minimized CSS and JS based on debug mode.

### [Config](https://github.com/kartik-v/yii2-krajee-base/blob/master/Config.php)
A global configuration and validation helper class for usage across Krajee's Yii 2 extensions.

##Latest Release
The latest version of the module is v1.0.0 released on 06-Nov-2014. Refer the [CHANGE LOG](https://github.com/kartik-v/yii2-krajee-base/blob/master/CHANGE.md) for details.

## Installation

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

> Note: Read this [web tip /wiki](http://webtips.krajee.com/setting-composer-minimum-stability-application/) on setting the `minimum-stability` settings for your application's composer.json.

Either run

```
$ php composer.phar require kartik-v/yii2-krajee-base "dev-master"
```

or add

```
"kartik-v/yii2-krajee-base": "dev-master"
```

to the ```require``` section of your `composer.json` file.

## License

**yii2-krajee-base** is released under the BSD 3-Clause License. See the bundled `LICENSE.md` for details.
