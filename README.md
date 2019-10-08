# slickjs
This module lets you use [Slick](https://github.com/kenwheeler/slick/) with Magento 2 throught requirejs

## Installation
```
composer require msp/slick
bin/magento setup:upgrade
```

## Usage
### Initialization
You can init the slider with `data-mage-init`:
```
<div class="your-class" data-mage-init='{
    "slick": {
      ...
      "autoplay"          :   true,
      ...
    }
}'>
  <div>your content</div>
  <div>your content</div>
  <div>your content</div>
</div>
```
or with a `<script type="text/x-magento-init">`:
```
<div id="your-id" class="your-class">
  <div>your content</div>
  <div>your content</div>
  <div>your content</div>
</div>
<script type="text/x-magento-init">
     {
         "#your-id": {
             "slick": {
                ...
                "autoplay"          :   true,
                ...
             }
         }
     }
 </script>

```
