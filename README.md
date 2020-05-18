简单的汉语转拼音类
===============

[![PHP Version](https://img.shields.io/badge/php-%3E%3D7.1-8892BF.svg)](http://www.php.net/)
[![Latest Stable Version](https://poser.pugx.org/itxq/pinyin/version)](https://packagist.org/packages/itxq/pinyin)
[![Total Downloads](https://poser.pugx.org/itxq/pinyin/downloads)](https://packagist.org/packages/itxq/pinyin)
[![Latest Unstable Version](https://poser.pugx.org/itxq/pinyin/v/unstable)](//packagist.org/packages/itxq/pinyin)
[![License](https://poser.pugx.org/itxq/pinyin/license)](https://packagist.org/packages/itxq/pinyin)
[![composer.lock available](https://poser.pugx.org/itxq/pinyin/composerlock)](https://packagist.org/packages/itxq/pinyin)
  
### 开源地址：

[【GitHub:】https://github.com/itxq/pinyin](https://github.com/itxq/pinyin)

[【码云:】https://gitee.com/itxq/pinyin](https://github.com/itxq/pinyin)

### 扩展安装：

+ 方法一：composer命令 `composer require itxq/pinyin`

+ 方法二：直接下载压缩包，然后进入项目中执行 composer命令 `composer update` 来生成自动加载文件

### 引用扩展：

+ 当你的项目不支持composer自动加载时，可以使用以下方式来引用该扩展包

```
// 引入扩展（具体路径请根据你的目录结构自行修改）
require_once __DIR__ . '/vendor/autoload.php';
```

### 使用示例：

```
<?php

use itxq\pinyin\PinYin;

require __DIR__ . '/vendor/autoload.php';

// 全部转换
echo PinYin::make()->turn('中文 带空格');

// 仅输出拼音首字母
echo PinYin::make()->turnFirst('中文 带空格');
```
