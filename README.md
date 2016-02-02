# touch-or-click
## 2016 [Ændrew Rininsland](http://github.com/aendrew/) ([@aendrew](http://twitter.com/aendrew))

A [Polymer](http://www.polymer.io) component that renders "tap" if the device has touch capabilities,
or "click" if otherwise. Uses Modernizr.touchevents for detection;
usual [caveats](https://modernizr.com/download?touchevents-setclasses) apply.

### [documentation](http://aendrew.com/touch-or-click/components/touch-or-click/)
### [demo](http://aendrew.com/touch-or-click/components/touch-or-click/demo/)

## Usage

Import touch-or-click.html and Polymer (a vulcanized version with Polymer embedded is attached) and
then use as follows:

`<touch-or-click></touch-or-click>`

It will render either "tap" or "click" based on the which device is consuming the element.

## Attributes

You can configure the element via the following attributes:

* touch-text (string; default: "tap")
  * The text to render for touch devices
* click-text (string; default: "click")
  * The text to render for click devices
* cap (boolean; default: false)
  * Whether to capitalise the first letter.

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## TODO:

* Tests!
