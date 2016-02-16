# Grid System

Bootstrap offers a responsive Grid System. 

A Grid System divides a screen into multiple rows and columns. There is no restriction on the number of rows, but 
each row could contain up to 12 columns only. 

The column widths depend on the size of the screen they are displayed on. As the columns resize themselves dynamically 
based on the screen (including resized windows) they are displayed on, Bootstrap's grid system qualifies to offer a responsive design. 

### Creation

It is recommended to place all the rows and columns inside a container to ensure proper alignment and padding. 

Bootstrap offers two types of container classes

1. <b>container</b>, which creates a fixed-width container 
2. <b>container-fluid</b>, which creats a full-width fluid container

<b> Create a row in a fixed-width container </b>

```html
      <div class="container">
        <div class="row">
        </div>
      </div>
```

<b> Create columns </b>

Bootstrap offers four types of class prefixes to create columns for different screen sizes.

| class prefix   |      screen size      |  description |
|----------|:-------------:|------:|
| col-xs |  < 768px | extra small screens |
| col-sm |    >= 768px   |   smaller screens |
| col-md | >= 992px |   medium screens |
| col-lg | >=1200px |    larger screens |

Columns are created by specifying the number of columns (\<=12) to span followed by a screen size's class prefix.

A column attributed with class col-xs-4 inside a row implies that the column occupies 4 out of 12 equal divisions that a row is divided into. 

In the following snippet, a row is 

```html
      <div class="container">
        <div class="row">
          <div class="col-xs-4">
            Column 1
          </div>        

          <div class="col-xs-4">
            Column 2
          </div>        

          <div class="col-xs-4">
            Column 3
          </div>                  
        </div>
      </div>
```
