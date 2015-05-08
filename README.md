# Flexbox Mixins
Flexbox is awesome. Unfortunately, it's still new enough that the properties don't have consistent values across browsers. This is a set of LESS mixins that I wrote to make it cross-browser compatible and easy to use. Alternatively, if you are using Sass/SCSS, [Compass](http://compass-style.org/) has some excellent Flexbox mixins that are worth checking out.

Note: these mixins will only support IE 9 and beyond. IE 9 uses an early version of the Flexbox spec but IE8 has zero support. If you have to support IE8, you will need to do additional layout considerations to make that work. Also, I feel bad for you because that's no fun...

## How to use
- These mixins require LESS
- Inside your project, create a `main.less` file. In that file, add `@import "flexbox.less";` and you're good to go!

## Author
**Mike McBride**
- [http://www.twitter.com/mmcbride1007](http://www.twitter.com/mmcbride1007)
- [http://www.github.com/mmcbride1007](http://www.github.com/mmcbride1007)

# License

The MIT License (MIT)

  Copyright (c) 2015 @mmcbride1007

  Permission is hereby granted, free of charge, to any person obtaining a copy
  of this software and associated documentation files (the "Software"), to deal
  in the Software without restriction, including without limitation the rights
  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
  copies of the Software, and to permit persons to whom the Software is
  furnished to do so, subject to the following conditions:

  The above copyright notice and this permission notice shall be included in
  all copies or substantial portions of the Software.

  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
  IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
  FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
  AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
  LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
  OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
  THE SOFTWARE.
