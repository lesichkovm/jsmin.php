# jsmin.php

Minifies and combines Javasript files into a single HTTP request to reduce overhead

## Usage

Change your JavaScript include scripts from:

```html
<script src="/shared/js/jquery-1.12.4.min.js"></script>
<script src="/shared/js/bootstrap.min.js"></script>
<script src="/shared/js/main.js"></script>
```
to a single include script

```html
<script src="/jsmin/shared/js/jquery-1.12.4.min.js/shared/js/bootstrap.min.js/shared/js/main.js"></script>
```     

