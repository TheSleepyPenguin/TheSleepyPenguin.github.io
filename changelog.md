# Theme Changelog

* `/_includes/footer.html`
  * Line 1: Change colour to `blue-grey`, `base`
  * Line 3: Add in `<div>` tag, `style="padding-left:40px"`
* `_layouts/home.html`
  * Remove search buttons
  * Line 22 or 36: Change colour to teal
  * Line 39 or 53: Change colour to teal
* `/_layouts/post.html`
  * Set the image to `<div class="parallax"><img style="max-width: 10%; max-height: auto"; src="{{ site.baseurl }}/images/{{ page.banner | default: "default.png" }}"></div>`
  * Move `<h1 class="center white-text blog-title">{{ page.title }}</h1>` to after the image and before the content
    * Change `white` to `black`

* `/_sass/components/variables.scss`

  * 4 Cards
    * Line 104 to: `$card-link-color: color("shades", "white") !default;`
    * Line 105 to: `$card-link-color-light: darken($card-link-color, 20%) !default;`

* `/_sass/highlighting.scss`

  * Remove all lines with `font-weight: bold`

* `/_sass/page-styles.scss`

  * Remove section with just `font-family`- lines 14-16

* `/_includes/side-nav.html`

  * Change colour to `blue-grey`, `base`
  * Add `style="padding: 20px"` to title
  * Remove `<br><br>`
  * Remove all dividers, apart from the first and last one

* `/_sass/customize.scss`

  * Add:

    * ```css
      .videoWrapper {
      	position: relative;
      	padding-bottom: 56.25%; /* 16:9 */
      	padding-top: 25px;
      	height: 0;
      }
      .videoWrapper iframe {
      	position: absolute;
      	top: 0;
      	left: 0;
      	width: 100%;
      	height: 100%;
      }
      ```

    * Original from [here](https://css-tricks.com/NetMag/FluidWidthVideo/Article-FluidWidthVideo.php)

