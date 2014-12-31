aerial-mod
==========

Modified version of HTML5 UP Aerial Template

## Modifications

* Removed most of the animations
* Removed background overlay
* Changed background image
* Added grunt tasks for:
  * Code minimise (CSS, HTML, JS)
  * SASS compile
  * JS inline
* Added on hover background colour change for links
* Added on hover tooltips for links
* Greatly improved [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) rating of the template by:
  * Re-ordering external JS / CSS file includes (Rules: Prioritize visible content, Eliminate render-blocking JavaScript and CSS in above-the-fold content)
  * Minimise all the files (Rules: Minify CSS, Minify JavaScript)

## Installation

### Install the dependencies

```
npm install
```

### Run grunt

If `grunt-cli` is not already installed, install it:

```
npm install grunt-cli -g
```

Run:
```
grunt
```

See it in action:
[www.omer.london](http://www.omer.london)

Source theme: [HTML5 UP Aerial](http://html5up.net/uploads/demos/aerial/)
