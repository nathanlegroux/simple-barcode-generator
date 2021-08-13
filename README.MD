


## Generate Barcode with $_GET request named "nums"


```php


<style>

.barcode {
  background-color: rgb(300, 300, 300);
}

</style>
<?php $nums = $_GET['nums']; ?>
<img class="barcode" src="http://bwipjs-api.metafloor.com/?bcid=code128&text=<?php echo $nums ?>">


```

## Generate Barcode with $_POST request named "nums"

```php

<style>

.barcode {
  background-color: rgb(300, 300, 300);
}

</style>
<?php $nums = $_POST['nums']; ?>
<img class="barcode" src="http://bwipjs-api.metafloor.com/?bcid=code128&text=<?php echo $nums ?>">

```



## Live version here : https://arni.fr/barcode/

