# cloom

## About
cloom is a port of [Holman](http://zachholman.com)'s [boom](https://github.com/holman/boom) in Clojure. It manages
text snippets on the command line. Quoting Zach's description of boom:

> You can stash away text like URLs, canned responses, and important notes and then quickly copy them onto your clipboard, ready for pasting.

## Usage

```
$ cloom gif magic http://i.imgur.com/n5xR79B.gif
Cloom! magic in gif is http://i.imgur.com/n5xR79B.gif. Got it.

$ cloom magic
Cloom! Copied http://i.imgur.com/n5xR79B.gif to your clipboard.

$ cloom rm-item gif magic
Cloom! magic is gone forever.
```

## Contributing
Cloom was written just for fun, but if you want to contribute, pull requests are welcome.

## License

```
The MIT License (MIT)

Copyright (c) 2016 Victor Gama

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
