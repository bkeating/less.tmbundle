![TextMate Bundle Logo](https://github.com/bkeating/less.tmbundle/raw/master/logo.png)

# Syntax support for LESS (.less) CSS files in TextMate.

This Bundle gives you syntax support (highlighting/recognition) for the LESS 
dynamic stylesheet language. Nothing more. It's a stripped down version of 
[appden](https://github.com/appden) & [rsms](https://github.com/rsms)'s 
[less.tmbundle](https://github.com/appden/less.tmbundle). If you plan to use
the ruby gem use their repository instead of this one.

### No compiling support... Get off my lawn!

There are a few ways to use LESS in your projects and they all seem to fit into 
one of two categories;

*  **On demand** - [Client side](http://lesscss.org/#-client-side-usage) in the
   browser or [Server side](http://lesscss.org/#-server-side-usage) using 
   [Node.js](http://nodejs.org/).
   
*  **Pre-compiled** - Using a Ruby Gem (``sudo gem install less``) 
   or [Less.app](http://incident57.com/less/) on the desktop.

The original version of this bundle assumes you use the ruby gem and so every 
time you save a file it will compile the CSS or error out if you don't have the 
gem installed. I don't want to use the ruby gem. I use Less.app. I also noticed 
that while saving large files via the ruby gem equipped bundle, it would lock 
up my TextMate session until the CSS compilation was complete. By using my 
simple bundle and an external compiler such as Less.app you get rid of that 
lock up. You save time. You keep it gangsta.

![Screenshot of less.tmbundle in action](https://github.com/bkeating/less.tmbundle/raw/master/screenshot.png)

## Authors

* Rasmus Andersson <http://hunch.se/> rsms@github
* Ben Keating <http://bpk.deepdream.com/> bkeating@github
* Scott Kyle <http://appden.com/> appden@github

## License (MIT)

Copyright (c) 2010 Rasmus Andersson, Ben Keating and Scott Kyle

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
FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.