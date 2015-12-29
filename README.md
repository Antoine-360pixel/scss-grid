sass-grid
=========

This is a little light grid scss.

## Usage
- no compass require

```scss
@import "sq_grid";

// grid init
$cols: 6;
$grid_max_width: 1400px;
$grid_gutter: 25px;

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
