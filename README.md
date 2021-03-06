# CCMultipartReader

An Objective C wrapper for [multipart-parser](https://github.com/FooBarWidget/multipart-parser), Hongli Lai's C++ implementation of a simple and efficient multipart MIME message parser.

**NOTE**: This project only includes the wrapper class. You will also need to obtain [multipart-parser](https://github.com/FooBarWidget/multipart-parser) from its official repository.

**NOTE**: Because multipart-parser is built on the C++ Standard Library, be sure to link your binary with the `libstdc++.dylib` library when configuring your project targets.

# License

Copyright (c) 2011 [CodeCatalyst, LLC](http://www.codecatalyst.com/)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
