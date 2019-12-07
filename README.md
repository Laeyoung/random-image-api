[![Run on Ainize](https://ainize.ai/static/images/run_on_ainize_button.svg)](https://ainize.web.app/redirect?git_repo=github.com/Laeyoung/random-image-api)


> A simple random-image-api written in PHP.

## Getting started

**Live Version:** https://random-image-api.herokuapp.com/

```
$ git clone https://github.com/OblivionSan/random-image-api.git
```


You can edit/change the api to fit your preference. Do not request me to do it.

> API Path: **./assets/api/ri-api.php**

> Default Img Path: **./assets/images/**

```html
<?php require_once './assets/api/ri-api.php'; ?> <!-- Request API file. -->
<img src="<?php echo $path . $img ?>"/> <!-- Displays images. -->
```
```php
$path = './assets/images/'; //Change the img file path if needed.
```
## Built with
> [HTML](http://devdocs.io/html/)

> [CSS](http://devdocs.io/css/)

> [PHP](http://devdocs.io/php/)

## Author
- **OblivionSan** - [@OblivionSan](https://twitter.com/OblivionSan) | [Discord Server](https://discord.gg/kxNeGRC) | [Website](https://oblivionsan.tk)
