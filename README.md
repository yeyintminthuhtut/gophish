![gophish logo](https://raw.github.com/gophish/gophish/master/static/images/gophish_purple.png)

gophish
=======

[![Join the chat at https://gitter.im/gophish/gophish](https://badges.gitter.im/gophish/gophish.svg)](https://gitter.im/gophish/gophish?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Build Status](https://travis-ci.org/gophish/gophish.svg?branch=master)](https://travis-ci.org/gophish/gophish) [![GoDoc](https://godoc.org/github.com/gophish/gophish?status.svg)](https://godoc.org/github.com/gophish/gophish)

Open-Source Phishing Toolkit

[Gophish](https://getgophish.com) is an open-source phishing toolkit designed for businesses and penetration testers. It provides the ability to quickly and easily setup and execute phishing engagements and security awareness training.

###Current Status
**Update 02/9/2016**

The [website is live](https://getgophish.com)! This website contains all the documentation and updates for gophish activity.

Gophish version 0.1.1 [has been released!](https://github.com/gophish/gophish/releases/tag/v0.1.1). Just download and run the binary to take gophish for a spin.

###Install

Installation of gophish is dead-simple - just download and extract the zip containing the [release for your system](https://github.com/gophish/gophish/releases/), and run the binary. Gophish has binary releases for Windows, Mac, and Linux platforms.

### Building From Source
**If you are building from source, please note that Gophish requires Go v1.5 or above!**

To build gophish from source, simply run ```go get github.com/gophish/gophish``` and ```cd``` into the project source directory. Then, run ```go build```. After this, you should have a binary called ```gophish``` in the current directory.

### Docker
You can also use gophish via an unofficial Docker container [here](https://hub.docker.com/r/matteoggl/gophish/).

###Setup
After running the gophish binary, open an Internet browser to http://localhost:3333 and login with the default username (admin) and password (gophish).

###Documentation

Documentation can be found on our [site](http://getgophish.com/documentation). Find something missing? Let us know by filing an issue!

###Issues

Find a bug? Want more features? Find something missing in the documentation? Let us know! Please don't hesitate to [file an issue](https://github.com/gophish/gophish/issues/new) and we'll get right on it.

###License
```
gophish - Open-Source Phishing Framework

The MIT License (MIT)

Copyright (c) 2013 - 2016 Jordan Wright

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software ("Gophish Community Edition") and associated documentation files (the "Software"), to deal
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
```
