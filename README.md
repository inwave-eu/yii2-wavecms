Yii 2 WaveCMS
=============

WaveCMS is content management system based on  [Yii 2](http://www.yiiframework.com/) and [Yii 2 Advanced Application Template](https://github.com/yiisoft/yii2-app-advanced)


Installing using Composer
-------------------------

1. Install application using following command: 
```
TO CHANGE
composer global require "fxp/composer-asset-plugin:^1.3.1"
composer create-project --prefer-dist mariuszstroz/yii2-wavecms my-project
```

2. Open a console terminal, execute the init command

```
/path/to/php-bin/php /path/to/yii-application/init
```

3. Create a new database and adjust the `components['db']` configuration in `common/config/main-local.php` accordingly.

4. Open a console terminal, apply migrations with command 
```
/path/to/php-bin/php /path/to/yii-application/yii migrate`.
```