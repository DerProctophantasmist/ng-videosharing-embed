# ng-videosharing-embed

Embed videos using AngularJS directives

[![Build Status](https://travis-ci.org/erost/ng-videosharing-embed.png?branch=master)](https://travis-ci.org/erost/ng-videosharing-embed)
***

## Purpose

A small project I've started while learning angularJS. It has no real purpose other than educational.

[![Support via Gittip](https://rawgithub.com/twolfson/gittip-badge/0.2.0/dist/gittip.png)](https://www.gittip.com/erost/)

## Usage

### Install

* `$ bower install ng-videosharing-embed`

Once installed, add videosharing-embed as a dependency in your module:

* `angular.module('myModule', ['videosharing-embed']);`

### Requirements

* **AngularJS v1.0.0+** is supported

### Supported Video Sources

* **Youtube** (iframe)
* **Youtube no cookies** (iframe)
* **Dailymotion** (iframe)
* **Vimeo** (iframe, JS API support)
* **Youku** (iframe, tentative)

### Test

Generic
```html
<embed-video href="<videoUrl>" width=xxx height=xxx [options]></embed-video>
```

Example
```html
<embed-video data-ng-href="http://www.youtube.com/watch?v=LOKyEt36Kjc" controls=0><a href="http://www.youtube.com/watch?v=LOKyEt36Kjc">Watch</a></embed-video>
```

Player's options are unique for each video source.
For a list of available options, take a look at src/angular-embedplayer.js
