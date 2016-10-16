Bootstrap Float Label
=====================

[![npm version](https://img.shields.io/npm/v/bootstrap-float-label.svg)](https://www.npmjs.com/package/bootstrap-float-label)

> Now part of [Bootstrap Kit](https://bootstrap-kit.highweb.tech/)!

Pure CSS implementation of Float Label pattern for **Bootstrap 4** powered by [Pure-CSS Float Label](https://github.com/tonystar/float-label-css).

[Switch to Bootstrap 3](https://github.com/tonystar/bootstrap-float-label/tree/v3-dev)

<img src="https://cdn.rawgit.com/tonystar/bootstrap-float-label/aced600/bootstrap-float-label.png" width="432"/>


## Demo

https://codepen.io/tonystar/pen/LRdpYZ


## Usage

Include `bootstrap-float-label.min.css`:
```html
<link rel="stylesheet" href="https://cdn.rawgit.com/tonystar/bootstrap-float-label/v4.0.0/dist/bootstrap-float-label.min.css"/>
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

ANY browser. See [Pure-CSS Float Label docs](https://github.com/tonystar/float-label-css#browser-support) for more details.
