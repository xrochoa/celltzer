# Celltzer
A Sass Grid System based on Bootstrap.
+ clean
+ easy to customize
+ not bloated

## 1. Use box/box-flow > line > cells
+ box is static
+ box-flow is fluid

Example 1:

```html
   <div class="box">
      <div class="line">
        <div class="cell xs-50"></div>
        <div class="cell xs-50"></div>
      </div>
    </div>
```

## 2. Responsive design:
+ xs for smartphone and above
+ sm for ipad and above
+ md for medium desktop
+ sm for large desktop and above


Example 2:

```html
   <div class="box">
      <div class="line">
        <div class="cell xs-100 md-33"></div>
        <div class="cell xs-100 md-33"></div>
        <div class="cell xs-100 md-33"></div>
      </div>
    </div>
```
## License
Copyright (c) 2016. [Xavi Ro](http://www.xaviro.com). MIT License.
