# phantomjs-polyfill-findIndex

Array.prototype.findIndex polyfill for phantom.js based on https://github.com/tom-james-watson/phantomjs-polyfill

This is a polyfill for Array.prototype.findIndex which is missing from PhantomJS.


## Installation

```
    npm install --save-dev phantomjs-polyfill-find-index
```


## Usage

```
    require('phantomjs-polyfill')
```


## Usage with Karma

Include the polyfill directly in the files list of your karma.conf

```
    ...
    files: [
      './node_modules/phantomjs-polyfill-find-index/findIndex-polyfill.js',
      ...
    ]
    ...
```
