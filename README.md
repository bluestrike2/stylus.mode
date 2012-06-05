# Stylus Meets Coda 2

If you're writing regular CSS, you're missing out. It's like jumping into the harsh vacuum of space without a spacesuit: really dumb... even though just having the opportunity would be, admittedly, out of this world.

Using Less? Scss? They're half-measures for no real reason. Sass? Much smarter. But [Stylus](http://learnboost.github.com/stylus) is really the tool you need to look at. Everything else, well, just kind of sucks in comparison:

```
body
  display block
  color #333
  font-size $superbig
```

This is a (very early WIP) syntax highlighting mode for Coda 2. Eventually after we're done here I'll see about expanding it to a nifty plugin with cool features (once I figure out what those features might be... maybe integrated build command, etc.). Who knows?

## Todo

* Haven't had a chance to sit down without distractions to fix up a couple little things that are driving me nuts. But in a nutshell, works fine with standard themes. There are some non-standard scopes I've added (matching against selectors and what not) that I'm toying with for my own preferences. Later when I loop back through I'll add a list of those scopes for those who want to take advantage of them.
* Refactor how properties and their values get matched to better handle nested mixins and properties.
* Add support for [nib](http://visionmedia.github.com/nib) aliases

## Contributing

Feel free to fork and submit a pull request with detailed commit messages.

## MIT License

Copyright © 2012 Tom Stoecklein. Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.