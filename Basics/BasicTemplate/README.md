### Required Files

<b> Bootstrap </b>

http://getbootstrap.com/getting-started/#download

<b> jQuery </b>

Bootstrap requires jQuery for its JavaScript components to function. 

Bootstrap supports \>= IE 8.

jQuery, version 2 does not support \>= IE 8.

Therefore, get the latest version of jQuery in version 1 to include support for \>= IE 8.

### Ensuring complete compatibility

To ensure that Bootstrap is compatible with every kind of device, few meta tags and a reference to few scripts are necessary.

<b> Required Meta Tags </b>

1) <i>\<meta charset="utf-8"\></i>

The above meta tag with charset attribute lets the browser know that the content of the web page contains Unicode characters. 

2) <i>\<meta http-equiv="X-UA-Compatible" content="IE-edge"\></i>

When IE runs in compatibility mode, it uses older rendering engines that do not support all CSS properties. The meta tag above forces IE to use the latest rendering engine to display the content of the web page it is declared in. 

3) <i>\<meta name="viewport" content="width=device-width, initial-scale=1"\></i>

The above meta tag lets the browser scale the contents of the web page to consume all its available space in the browser window, including on a mobile, tablet or a desktop screen. 

The attribute initial-scale with value 1 indicates scaling to 100%.

<b> Reference to Required Scripts </b>

IE 8 is not capable of handling all HTML 5 and CSS 3 properties that Bootstrap makes use of. To bring this capability to IE 8, the scripts required are: html5shiv.js and respond.js, so add a reference to the required scripts' CDN.

```html
<!-- [if lt IE 9]>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/respond.js/1.4.2/respond.js"></script>
<![endif]-->
```

### Basic Template

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <title>Basic Bootstrap Template</title>
    <link rel="stylesheet" type="text/css" href="bootstrap-3.3.6-dist/css/bootstrap.css">

    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
      <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>
  <body>
      <h1>Welcome to Basic Bootstrap Template</h1>
    
    <script src="jquery/jquery-1.12.0.js"></script>
    <script src="bootstrap-3.3.6-dist/js/bootstrap.js"></script>
  </body>
</html>
```

### Verify

<img src="_misc/check%20to%20see%20if%20files%20were%20delivered.png"/>
