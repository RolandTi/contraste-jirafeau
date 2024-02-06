# contraste-jirafeau

 A black & white theme for Jirafeau

## install

Edit the config.local.php file with : 

```php
  'style' => 'contraste',
  'dark_style' => 'contraste',
```

to make the theme responsive, you need to edit the file `/lib/template/header.php` and add before `</head>` :

```html
  <meta name="viewport" content="width=device-width,initial-scale=1"/>
```

that's all folks !
