Bootstrap Float Label
=====================

Pure CSS implementation of Float Label pattern for Bootstrap 3 powered by [Float Label CSS-only](https://github.com/tonystar/float-label-css).

[Switch to Bootstrap 4](https://github.com/tonystar/bootstrap-float-label)

<img src="https://cdn.rawgit.com/tonystar/bootstrap-float-label/0ab4260/bootstrap-float-label.png" width="374"/>


## Demo

https://codepen.io/tonystar/pen/ALaZrV


## Usage

Include `bootstrap-float-label.min.css`:
```html
<link rel="stylesheet" href="https://cdn.rawgit.com/tonystar/bootstrap-float-label/v3.0.1/dist/bootstrap-float-label.min.css"/>
```

Then just add `.has-float-label` class to `.form-group`:
```html
<span class="form-group has-float-label">
  <input class="form-control" id="email" type="email" placeholder="email@example.com"/>
  <label for="email">Email</label>
</span>
```

**NOTE:** `label` should go after `input`! This is the only drawback in this method.

Using inside `.input-group` is also supported:
```html
<div class="form-group input-group">
  <span class="has-float-label">
    <input class="form-control" id="first" type="text" placeholder="Name"/>
    <label for="first">First</label>
  </span>
  <span class="has-float-label">
    <input class="form-control" id="last" type="text" placeholder="Surname"/>
    <label for="last">Last</label>
  </span>
</div>
```


## Browser support

ANY browser. See [Float Label CSS-only docs](https://github.com/tonystar/float-label-css#browser-support) for more details.
