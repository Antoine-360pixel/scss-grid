sass-grid
=========

This is a light grid scss, customizable and very easy to use.

### How to install:

Using **bower**:

```
bower i scss-grid --save
```

## Usage
- no compass require

```scss
@import "sq-grid";

// grid init
$cols: 6;
$grid_max_width: 1400px;
$grid_gutter: 25px;
$breakpoint: 1024px;

```

##Example

With html:
```html
<main class="fluid-row">
  <div class="col-3"></div>
  <div class="col-3"></div>
</main>
```

With Scss:
```scss
.box {
  @extend col(3);
}
```

## License
No license ! Enjoy
