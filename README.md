# bottom-bar

A button bar fixed to the bottom of the viewport.
---

![picture alt](https://cdn.jsdelivr.net/gh/terrymorse58/bottom-bar/Docs/bottom-bar.png "Title is optional")

## Usage

```html
  <!-- use fontawesome regular for icons -->
<link
  href="https://cdn.jsdelivr.net/gh/terrymorse58/bottom-bar/fontawesome/css/fontawesome.css"
  rel="stylesheet">
<link
  href="https://cdn.jsdelivr.net/gh/terrymorse58/bottom-bar/fontawesome/css/regular.css"
  rel="stylesheet">

<!-- link to the bottom-bar style sheet -->
<link
  href="https://cdn.jsdelivr.net/gh/terrymorse58/bottom-bar/bottombar.css"
  rel="stylesheet">

<!-- optional: edit any of the styles *after* linking bottombar.css -->
<style>
  :root {
    --bb-background-color: darkgreen;
  }
</style>
```

Then in the HTML body:
```html
<div class="bottom-bar">
  <button>
    <i class="far fa-angry"></i><br>
    angry!
  </button>
  <button>
    <i class="far fa-thumbs-up"></i><br>
    like
  </button>
  <button>
    <i class="far fa-heart"></i><br>
    love
  </button>
  <button>
    <i class="far fa-window-close"></i><br>
    close
  </button>
  <div>some<br>
    text</div>
</div>

```
