# CSS OPACITY

  Mobile-first classes for css-opacity.
  Set the desired css-opacity on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-opacity
```
or download the css on github and include in your project.

## File Size


## The Code
```
.o-10 { opacity: .1; }
.o-20 { opacity: .2; }
.o-30 { opacity: .3; }
.o-40 { opacity: .4; }
.o-50 { opacity: .5; }
.o-60 { opacity: .6; }
.o-70 { opacity: .7; }
.o-80 { opacity: .8; }
.o-90 { opacity: .9; }
.o-full { opacity: 1; }

@include break(not-small) {
  .o-10-ns { opacity: .1; }
  .o-20-ns { opacity: .2; }
  .o-30-ns { opacity: .3; }
  .o-40-ns { opacity: .4; }
  .o-50-ns { opacity: .5; }
  .o-60-ns { opacity: .6; }
  .o-70-ns { opacity: .7; }
  .o-80-ns { opacity: .8; }
  .o-90-ns { opacity: .9; }
  .o-full-ns { opacity: 1; }
}

@include break(medium) {
  .o-10-m { opacity: .1; }
  .o-20-m { opacity: .2; }
  .o-30-m { opacity: .3; }
  .o-40-m { opacity: .4; }
  .o-50-m { opacity: .5; }
  .o-60-m { opacity: .6; }
  .o-70-m { opacity: .7; }
  .o-80-m { opacity: .8; }
  .o-90-m { opacity: .9; }
  .o-full-m { opacity: 1; }
}

@include break(large) {
  .o-10-l { opacity: .1; }
  .o-20-l { opacity: .2; }
  .o-30-l { opacity: .3; }
  .o-40-l { opacity: .4; }
  .o-50-l { opacity: .5; }
  .o-60-l { opacity: .6; }
  .o-70-l { opacity: .7; }
  .o-80-l { opacity: .8; }
  .o-90-l { opacity: .9; }
  .o-full-l { opacity: 1; }
}

```

## Author

[http://mrmrs.cc](http://mrmrs.cc - Entire internet gateway to all things mrmrs)
[http://mrmrs.io](http://mrmrs.io - Open source projects)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

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

