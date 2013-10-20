# Local Markdown Preview

## Getting Started

1. Install Node.js 0.10.x (e.g. `nodebrew install-binary v0.10`)
2. Install Bower 1.2.7 (`npm install -g bower@1.2.7`)
3. Install dependent packages with Bower (`bower install`)
4. Open `index.html` with your web browser.

## How to make Standalone `index.html`

1. Install **Make**
2. Install [UglifyJS](https://github.com/mishoo/UglifyJS) 2.4.0 (`npm install -g uglify-js@2.4.0`)
3. Execute `cd bower_components/marked && make && cd ../../`
4. Copy `bower_components/marked/marked.min.js` and paste it into script tag

### TODO

* Enable to do this operation automatically

## License

Copyright (c) ka (http://kaosfield.net)

[MIT](http://opensource.org/licenses/MIT)

* `index.html` of [markdown.js](https://github.com/evilstreak/markdown-js): Copyright (c) evilstreak (http://dominicbaggott.com, https://github.com/evilstreak) (MIT)

* [marked.js](https://github.com/chjj/marked): Copyright (c) 2011-2013, Christopher Jeffrey (https://github.com/chjj/) (MIT)
