Bootstrap Float Label
=====================

[![npm version](https://img.shields.io/npm/v/bootstrap-float-label.svg)](https://www.npmjs.com/package/bootstrap-float-label)
[![codepen](https://img.shields.io/badge/code-pen-d3d3d3.svg)](https://codepen.io/tonystar/pen/LRdpYZ)

> Now part of [Bootstrap Kit](https://bootstrap-kit.com/)!

Pure CSS implementation of Float Label pattern for **Bootstrap 4** powered by [Pure-CSS Float Label](https://github.com/tonystar/float-label-css).

[Switch to Bootstrap 3](https://github.com/tonystar/bootstrap-float-label/tree/v3-dev)

<img src="https://cdn.rawgit.com/tonystar/bootstrap-float-label/aced600/bootstrap-float-label.png" width="432"/>


## Note!

As of v4.0.2 files from `dist` folder are moved to project root! Be careful and update your paths!


## Demo

https://codepen.io/tonystar/pen/LRdpYZ


## Usage

Include `bootstrap-float-label.min.css`:
```html
<link rel="stylesheet" href="https://cdn.rawgit.com/tonystar/bootstrap-float-label/v4.0.2/bootstrap-float-label.min.css"/>
```

Then just add `.has-float-label` class to `.form-group` <sup>**v4.0.1+**</sup>:
```html
<label class="form-group has-float-label">
  <input class="form-control" type="email" placeholder="email@example.com"/>
  <span>Email</span>
</label>
```

**NOTE:** `<input>` should be inside `<label>` and `<span>` should go after `<input>`. [Why?](https://github.com/tonystar/float-label-css#usage)

Using inside `.input-group` is also supported:
```html
<div class="form-group input-group">
  <label class="has-float-label">
    <input class="form-control" type="text" placeholder="Name"/>
    <span>First</span>
  </label>
  <label class="has-float-label">
    <input class="form-control" type="text" placeholder="Surname"/>
    <span>Last</span>
  </label>
</div>
```


## Browser support

ANY browser. See [Pure-CSS Float Label docs](https://github.com/tonystar/float-label-css#browser-support) for more details.
