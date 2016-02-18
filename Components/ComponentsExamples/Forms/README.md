### Forms

To create a form, use the "form" element with "form" class. 
To add a label and an input/textarea field to the form, enclose them in a div element with "form-group" class.

Notice, the value of "for" attribute in a label tag is same as the value of "id" attribute of the input/textarea control 
following it.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <title>Basic Bootstrap Template</title>
    <link rel="stylesheet" type="text/css" href="../bootstrap-3.3.6-dist/css/bootstrap.css">

    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
      <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>
  <body>
      <form class="form">                 <-----------
        <div class="form-group">
          <label for="username">Username</label>
          <input type="text" id="username" placeholder="username"/>
        </div>
      </form>
    
    <script src="../jquery/jquery-1.12.0.js"></script>
    <script src="../bootstrap-3.3.6-dist/js/bootstrap.js"></script>
  </body>
</html>
```

To make the input element full width, attach class "form-control" to it

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <title>Basic Bootstrap Template</title>
    <link rel="stylesheet" type="text/css" href="../bootstrap-3.3.6-dist/css/bootstrap.css">

    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
      <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>
  <body>
      <form class="form">
        <div class="form-group">
          <label for="username">Username</label>
          <input type="text" class="form-control" id="username" placeholder="username"/>  <----------
        </div>
      </form>
    
    <script src="../jquery/jquery-1.12.0.js"></script>
    <script src="../bootstrap-3.3.6-dist/js/bootstrap.js"></script>
  </body>
</html>
```

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <title>Basic Bootstrap Template</title>
    <link rel="stylesheet" type="text/css" href="../bootstrap-3.3.6-dist/css/bootstrap.css">

    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
      <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>
  <body>
      <form class="form">

        <!-- username -->
        <div class="form-group">
          <label for="username">Username</label>
          <input type="text" class="form-control" id="username" placeholder="username"/>
        </div>

        <!-- email -->
        <div class="form-group">
          <label for="emailId">Email ID</label>
          <input type="email" class="form-control" id="emailId" placeholder="Email ID"/>
        </div>

        <!-- comments -->
        <div class="form-group">
          <label for="comments">Comments</label>
          <textarea type="text" class="form-control" id="comments" placeholder="Place your comments here ..."></textarea>
        </div>

        <!-- buttons -->
        <button type="submit" class="btn btn-primary">Submit</button>
        <button type="reset" class="btn btn-primary">Reset</button>

      </form>
    
    <script src="../jquery/jquery-1.12.0.js"></script>
    <script src="../bootstrap-3.3.6-dist/js/bootstrap.js"></script>
  </body>
</html>
```
