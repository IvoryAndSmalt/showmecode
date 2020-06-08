# Image d'une maquette en background

##### HTML

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      body {
        margin: 0;
      }
      .img_bg {
        background: url("votreimage") no-repeat center top;
        height: 3455px;
      }
      @media screen and (max-width: 1199px) {
        .img_bg {
          background-size: 1440px 2591px;
          height: 2591px;
        }
      }
      @media screen and (max-width: 900px) {
        .img_bg {
          background-size: 960px 1727px;
          height: 1727px;
        }
      }
      @media screen and (max-width: 900px) {
        body {
          min-width: 600px;
        }
      }
    </style>
  </head>
  <body>
    <div class="img_bg"></div>
  </body>
</html>
```
