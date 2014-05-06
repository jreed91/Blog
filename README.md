# About this Repo #

This is the default installment - with minor personal tweaks - of [Jekyll](http://jekyllrb.com/), using [Sass](http://sass-lang.com/) and [Compass](http://compass-style.org/) to precompile CSS and help development. This is the set up I use when studying/working.

Clone it:

    git clone git://github.com/israveri/jekyll-sass-compass.git site

Bundle it:

    bundle install

Run it:

    jekyll serve -w

Work on it!

* * *

The directory structure goes as follow:

> |-- assets
> |&nbsp;&nbsp;&nbsp;|-- css
> |&nbsp;&nbsp;&nbsp;|-- img
> |&nbsp;&nbsp;&nbsp;|-- js
> |
> |-- _sass
> |&nbsp;&nbsp;&nbsp;|-- config.rb
> |
> |-- \*default jekyll files/folders\*

&nbsp;

+ **assets** is where the compiled css will be outputed, as well as your scripts and images are put.
+ **_sass** is the folder where *.scss files live.
+ **config.rb** is sass configuration file with the assets folder already configured.


* * *

Feel free to fork, contribute, comment, star and/or sacrifice to a pagan god. You're much welcome to do so.

# Slim Support

If you want to use [Slim](http://slim-lang.com/) to generate your pages, clone the slim branch with:

    git clone git://github.com/israveri/jekyll-sass-compass -b slim /folder/name

# License #

License
Copyright (c) 2013 Israel Ribeiro

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.