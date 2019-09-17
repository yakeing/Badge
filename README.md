<div align=center><img src="https://raw.githubusercontent.com/yakeing/php_badge/master/Subsidiary/SVG.png"/></div>

# Badge
This is an identification tag based on SVG, It can quickly generate various labels and status identifiers

### Hits Example

[![Hits](https://oauth.applinzi.com/Hits/yakeing/php_badge/null.svg)](https://github.com/yakeing/php_badge)

```
    https://example.com/Hits/{USERNAME}/{PROJECT}/null.svg
    
    ++$count;
    array(
     array('hits','555555'),
     array($count,'4C1')
    );
    
    //test example
    //https://oauth.applinzi.com/Hits/yakeing/php_badge/null.svg
```

---

### Server Example

[![Server](https://oauth.applinzi.com/Server/yakeing/index/null.svg)](https://github.com/yakeing/php_badge)

```
    https://example.com/Server/{USERNAME}/{PROJECT}/null.svg
    
    array(
     array('{OS}','555555'),
     array('CPU: {CPU}','A0ABFC'),
     array('RAM: {RAM}','F0A010')
    );
    
    //test example
    //https://oauth.applinzi.com/Server/yakeing/index/null.svg
    
```

---

### State Example

[![error](https://oauth.applinzi.com/State/error/ERROR/ed1941.svg)](https://github.com/yakeing/php_badge)
[![rocket](https://oauth.applinzi.com/State/rocket/PASSED/28a745.svg)](https://github.com/yakeing/php_badge)
[![hearts](https://oauth.applinzi.com/State/hearts/LOVE/ea4c89.svg)](https://github.com/yakeing/php_badge)
[![thumb](https://oauth.applinzi.com/State/thumb/88888/636AD0.svg)](https://github.com/yakeing/php_badge)
[![passed](https://oauth.applinzi.com/State/passed/PASSED/44CC11.svg)](https://github.com/yakeing/php_badge)

```
    https://example.com/Label/{LOGO}/{MESSAGE}/{COLOR}.svg
    
    //get logo file
    $Badge->Icon = file_get_contents({LOGO}); //<path d="M23....." fill="#FFF"></path>
    $Badge->viewBox = '-120 -85 1200 1200'; //Svg Icon x, y, Width, Height
    $Badge->opacity = 0.7; //transparency (0 - 1)
    
    array(
     array({MESSAGE},{COLOR})
    );
    
    //test example
    //https://oauth.applinzi.com/State/passed/PASSED/44CC11.svg
```

---

### Label Example

[![tag](https://oauth.applinzi.com/Label/tag/V4.1.0/28a745.svg)](https://github.com/yakeing/php_badge/releases)
[![license](https://oauth.applinzi.com/Label/license/MPL-2.0/FE7D37.svg)](https://github.com/yakeing/php_badge/blob/master/LICENSE)
[![languages](https://oauth.applinzi.com/Label/languages/php/007EC6.svg)](https://github.com/yakeing/php_badge/search?l=php)
[![star](https://oauth.applinzi.com/Label/star/999/de773f.svg)](https://github.com/yakeing/php_badge/stargazers)
[![fork](https://oauth.applinzi.com/Label/fork/999/8552a1.svg)](https://github.com/yakeing/php_badge/network/members)
[![github](https://oauth.applinzi.com/Label/github/Active/28a745.svg)](https://github.com/yakeing/php_badge/deployments)

```
    https://example.com/Label/{LABEL}/{MESSAGE}/{COLOR}.svg
    
    $Badge->Icon = file_get_contents({LOGO}); //<path d="M23....." fill="#FFF"></path>
    array(
     array({LABEL},'555555'),
     array({MESSAGE},{COLOR})
    );
    
    //test example
    //https://oauth.applinzi.com/Label/license/MPL-2.0/FE7D37.svg
```

---

### Travis CI

[![Travis-ci](https://api.travis-ci.org/yakeing/php_badge.svg)](https://travis-ci.org/yakeing/php_badge)

### codecov

[![codecov](https://codecov.io/gh/yakeing/php_badge/branch/master/graph/badge.svg)](https://codecov.io/gh/yakeing/php_badge)

### Packagist

[![Version](http://img.shields.io/packagist/v/yakeing/php_badge.svg)](https://github.com/yakeing/php_badge/releases)
[![Downloads](http://img.shields.io/packagist/dt/yakeing/php_badge.svg)](https://packagist.org/packages/yakeing/php_badge)

### Github

[![Downloads](https://img.shields.io/github/downloads/yakeing/php_badge/total.svg)](https://github.com/yakeing/php_badge)
[![Size](https://img.shields.io/github/size/yakeing/php_badge/src/Badge.php.svg)](https://github.com/yakeing/php_badge/blob/master/src/Badge.php)

### Installation

Use [Composer](https://getcomposer.org) to install the library.

```
    $ composer require yakeing/php_badge
```

### Initialization parameter

- [x] Sample：
```php

    $arr = array(
        array('build', '555'), //#555555
        array('passing', '4c1'), //#44CC11
        ..........
    );

    $Badge = new Badge();
    $Badge->svg($arr);

```

Donate
---
If you've got value from any of the content which I have created, then I would very much appreciate your support by payment donate.

 [Bitcoin](https://btc.com/1FYbZECgs3V3zRx6P7yAu2nCDXP2DHpwt8)

 1FYbZECgs3V3zRx6P7yAu2nCDXP2DHpwt8

 ![Bitcoin](https://raw.githubusercontent.com/yakeing/Content/master/Donate/Bitcoin.png)

 WeChat

 ![WeChat](https://raw.githubusercontent.com/yakeing/Content/master/Donate/WeChat.png)

 Alipay

 ![Alipay](https://raw.githubusercontent.com/yakeing/Content/master/Donate/Alipay.png)

Author
---

weibo: [yakeing](https://weibo.com/yakeing)

twitter: [yakeing](https://twitter.com/yakeing)
