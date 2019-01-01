# Mediumish Theme Changelog

* Add responsive video CSS to `assets/css/main.scss`

* Add the following to `assets/css/main.scss` to make line breaks visible

  ```scss
  hr {
  	background-color: rgba(255,255,255,0.3);
  }
  ```

* Remove `// alertbar later` section in `assets/js/mediumish.js`

* Remove unnecessary items navigation bar items in `_layouts/default.html`

* Make sure that `navbar-dark` and `bg-dark` is set in Menu Navigation in `_layouts/default.html`

* Change footer colour text in `_layouts/default.html`

  ```html
  <div class="col-md-6 col-sm-6 text-center text-lg-left"; style="color: #ffffff">
                   Copyright © {{ site.time | date: "%Y" }} {{ site.name }} 
              </div>
              <div class="col-md-6 col-sm-6 text-center text-lg-right"; style="color: #ffffff">    
                  <a target="_blank" href="https://www.wowthemes.net">Mediumish Theme</a> by WowThemes.net
              </div>
  ```

* Add the following to the `class="main_content"` section in `_layouts/default.html`:

  ```css
  <style>
      body {
          background-color: #212529;
          color: #ffffff;
      }
  </style>
  ```

* Change `.footer` background colour to `#212529` in `assets/css/screen.css`
* In `pre` set border colour to `#343a40`
* In `.section-title h2` and `.section-title span`, change the colour to `255`
  * Eg. `border-bottom:1px solid rgba(255,255,255,.44);`
  * Additionally in `.section-title h2`, change `font-weight` to 500
* In `.post-top-meta span`, change the colour to `color: rgba(255,255,255,.8)`
* Replace all `rgba(0,0,0,` with `rgba(255,255,255,`
* Replace all `font-weight:700` and `font-weight: 700` with `font-weight: 200`
* In `.article-post`, change `font-family` to `Quicksand`
* In `.article-post .h1, .article-post .h2, etc.` add `color: #ffffff`
  * Also, `font-weight` should be changed to 500
* Change `font-weight` in `.listfeaturedtag` to 400
* In `borderquote` remove `font-style:italics;`

* In `_includes/share.html`, change the root tag to include `style="color: #ffffff"`
* In `_layouts/post.html`:
  * Remove featured image section
  * Within `Author Box`, change `link-dark` to `link-light`
* In `_includes/featuredbox.html`:
  * Add  `bg-dark` to `<div class="card"`: `<div class="card bg-dark"`
* In `_includes/postbox.html` and `_includes/featuredbox.html`:
  * In `<h2 class="card-title"` change `text-light` to `text-dark`
  * In `<div class="card-footer` change `bg-light` to `bg-dark`
* In `_includes/postbox.html`:
  * Add `style="background-color: #212529"` in `<div class="card-body"`
  * Add `style="background-color: rgba(255,255,255,.15)` in `<div clas="card h-100`
* Change `_sass/_syntax.css` to [this](https://raw.githubusercontent.com/dracula/pygments/2d85ede1540db3739d5404343aa722f54e042141/dracula.scss)
  * Change background colour to `#212529`
* 

