img2css
=======

Convert arbitrary images into huge, browser-crashing CSS box-shadow settings.

Example
-------
[http://rmer.info/css\_mona\_lisa.html](http://rmer.info/css_mona_lisa.html) (your browser will likely not be happy with your decision to visit this link).


Usage
-----
* Don't, obviously

But I want to
-------------
* Edit img2css.js, change "img.src = 'mona.jpg'" to point to some (local) image resource you would like to make much more unwieldy
* Point a recent version of Firefox at example.html. The initial rendering seems to only work in Firefox, but the generated CSS "works" broadly among modern browsers
* You should see two copies of your image, possibly after a lengthy wait. Inspect the second one with Firebug to get a copy of its CSS attribute
* Dump the CSS into your stylesheet, under say .mona-lisa, go nuts
