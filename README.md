webfonts
========

Webfonts server for all Burmese fonts.

Usage
=====
```<?php
include_once('../WebFont-class.php');
$url = '';
$style-dir = 'wfstyles';
$font-dir = 'webfonts';

$webfont = new WebFont($url, $style-dir, $font-dir);

$webfont->redirect_css();
?>
```
