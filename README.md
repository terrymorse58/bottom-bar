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
    <i class="fal fa-map-marker-question"></i><br>
    where am i
  </button>
  <button>
    <i class="fal fa-thumbs-up"></i><br>
    like
  </button>
  <button>
    <i class="fal fa-cog"></i><br>
    settings
  </button>
  <button>
    <i class="fal fa-info-circle"></i><br>
    info
  </button>
  <div>some<br>
    text</div>
</div>

```
