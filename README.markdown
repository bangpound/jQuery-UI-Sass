jQuery UI Sass
==============

This project aims to be a near perfect re-implementation of jQuery UI styles in [Sass](http://sass-lang.com/). The styles rely on some [Compass](http://github.com/chriseppstein/compass) framework mixins.

Contents
--------
* `images` from jQuery UI base theme.
* `sass` Sass source
* `source-css` original jQuery UI css

Testing
-------
Compass will compile all stylesheets into the root of the project directory. This allows you to test the outcome with jQuery UI's demos that are distributed with the jQuery UI Development Bundle.

Goals
-----

1. <strike>Make Themeroller unnecessary.</strike> **done**
2. All widget styles are mixins. *partial*
3. Support RTL widgets.
