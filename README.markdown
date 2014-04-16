LESS version
============

This is the LESS version of ZURB's Foundation, which tooks advantage of the possibilities of the LESS CSS preprocessor.
You can learn more about LESS here: http://lesscss.org/

This version is maintained by Zoltán Adamek a.k.a. [scorchio](https://github.com/scorchio).


What Foundation is (from the original README)
=============================================

> Foundation is a rock-solid, responsive framework for rapidly prototyping and iterating into production code. It includes a 12-column, future-friendly grid and tons of great tools and elements that'll get you up and running in no time. Clone the repo to get the marketing site, docs, and base source. You can also visit http://foundation.zurb.com to download just the base source as a starting boilerplate.

>Homepage:      http://foundation.zurb.com
>Documentation: http://foundation.zurb.com/docs
>Download:      http://foundation.zurb.com/files/foundation-download-2.1.4.zip

>Foundation is MIT-licensed and absolutely free to use. Foundation wouldn't be possible without the support of the entire ZURB team, our friends and colleagues who gave feedback, and some luminaries who did some heavy lifting that we took advantage of (thanks guys).


Advices and notes for the LESS version
======================================

* Please note that this version is still in heavy development. I do my best to make sure that this version will output a functionally equivalent Foundation, but *minor differences can occur*. If you think something is wrong, please file an issue!
* I personally recommend to use the JS version in the header for development, but after that, it would be wise to use the lessc binary and minify the CSS output.
* I've included both the minified and the non-minified version of LESS.js, use whichever you prefer to work with.
* I'm planning to keep this in sync with all the included projects, but don't expect the bleeding edge version of Foundation here all the time :)

Repo Contents
=============

* README
* IMAGES - Base images for Orbit and some standard elements
* INCLUDES - Header and footer (currently PHP)
* index.php
* JAVASCRIPTS - jQuery, app.js placeholder, LESS.js (development and minified versions)
* MARKETING - the entire marketing site (foundation.zurb.com)
* robots.txt - Boilerplate robots file
* STYLESHEETS - the LESS version of the Foundation stylesheets

To do
=====
* Integrate the HelpLess Helper Library, so that we can use simple markup without worrying about vendor prefixes etc.
* Modify HelpLess: .reset, .normalize, .clearfix. Normalization should be done in a way like [m6tt's LESS Boilerplate](https://github.com/m6tt/less-boilerplate/blob/less/less/libs/boilerplate.less), so that we can customize basic settings of Foundation via normalize.

Development Log
===============

6th Jan, 2012 - I'm almost done with LESSifying the original Foundation CSS files. That means the original syntax is cleaned up in the LESS way; I've only made smaller refactorings to take advantage of LESS and prepare further work.

MIT Open Source License
=======================

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
