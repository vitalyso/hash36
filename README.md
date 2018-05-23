Hash36
======

Hash36 example:

```php
$h36 = new Hash36();
var_dump($h36->encode(1)); //string 'BKPXGK' (length=6)
var_dump($h36->decode('BKPXGK')); //string '1' (length=1)
```
