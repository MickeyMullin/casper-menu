# Casper Menu

[Casper](https://github.com/TryGhost/Casper) is the default theme for [Ghost](http://github.com/tryghost/ghost/). So far, I've added changes done by [Jason Friedrich](http://friedrich.org.uk) from his [GitHub repo](https://github.com/jbfriedrich/casper-menu "Casper Menu") in order to add some static page buttons. I forked from Ghost's main hub rather than jbfriedrich's, so that I could more easily incorporate updates to the main theme, but I've named my fork in honor of jbfriedrich's inspiration.

### Roadmap
Additional updates that I plan to add to Ghost/Casper include:

* Search
* Social bar (Twitter, Facebook, etc.)
* Social integration (automatic optional posting to the above)
* Ads integration (Google, Bing) (Hey, they're what make things feel like they're "free," right?)
* Making the "menu" configurable in the admin area
* Playing more nicely with blog logos

(These are not in order of priority.)

### Installation
Until I add more features, the only additional necessary step is editing Ghost's `.gitmodules` to point here (or to your own fork) instead of the primary:

	[submodule "content/themes/casper"]
		path = content/themes/casper
		url = https://github.com/MickeyMullin/casper-menu.git

And then a `git submodule update`

## Copyright & License

Copyright (c) 2013-2014 Ghost Foundation - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
