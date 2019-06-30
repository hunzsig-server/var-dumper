[![License](https://img.shields.io/github/license/yonna-framework/var-dumper.svg)](https://packagist.org/packages/yonna/var-dumper)
[![Repo Size](https://img.shields.io/github/repo-size/yonna-framework/var-dumper.svg)](https://packagist.org/packages/yonna/var-dumper)
[![Downloads](https://img.shields.io/packagist/dm/yonna/var-dumper.svg)](https://packagist.org/packages/yonna/var-dumper)
[![Version](https://img.shields.io/github/release/yonna-framework/var-dumper.svg)](https://packagist.org/packages/yonna/var-dumper)
[![Php](https://img.shields.io/packagist/php-v/yonna/var-dumper.svg)](https://packagist.org/packages/yonna/var-dumper)

## Yonna var-dumper库

```
Yonna是一个极其纯净的纯API-PHP框架.
var-dumper库是yonna专用dumper包
源于Symfony VarDumper
```

## 

#### 如何安装

##### 可以通过composer安装：`composer require yonna/var-dumper`

##### 可以通过git下载：`git clone https://github.com/yonna/var-dumper.git`

> Yonna demo：[GOTO yonna](https://github.com/yonna-framework/yonna)

### Dumper

> 使用Vardumper打印你的参数吧
```php
<?php
    $str = 'hello yonna';
    $obj = [
        'code' => 'object yonna'
    ];
    dump($str);
    dump($obj);
    dd($obj);
?>
```

##### 资源

  * [Symfony VarDumper文档](https://symfony.com/doc/current/components/var_dumper/introduction.html)
  * [感谢贡献](https://symfony.com/doc/current/contributing/index.html)
