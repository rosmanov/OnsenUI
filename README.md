# Onsen UI 

[![Join us on Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/OnsenUI/OnsenUI)
[![StackOverflow](http://img.shields.io/badge/stackoverflow-onsen--ui-FF412D.svg )]( http://stackoverflow.com/questions/tagged/onsen-ui)
[![TypeScript definitions on DefinitelyTyped](http://definitelytyped.org/badges/standard.svg)](https://github.com/borisyankov/DefinitelyTyped/tree/master/onsenui)
[![Circle CI](https://circleci.com/gh/OnsenUI/OnsenUI.svg?style=shield)](https://circleci.com/gh/OnsenUI/OnsenUI) 
[![Coverage Status](https://coveralls.io/repos/OnsenUI/OnsenUI/badge.svg?branch=master&service=github)](https://coveralls.io/github/OnsenUI/OnsenUI?branch=master)

The best place to start with Onsen UI is our [Getting Started](http://onsen.io/guide/getting_started.html) page.

![The Answer to PhoneGap UI Development](https://cloud.githubusercontent.com/assets/9889313/5350569/eec8b870-7efb-11e4-90af-2f4d505e09a8.png)

Built on top of [AngularJS](http://angularjs.org/), Onsen UI is open source, free and open for all. Onsen UI is designed and implemented to deliver unprecedented user experience for your apps. Applications can be built using **HTML tags** web developers already know and love. We love AngularJS and all the power it brings. But we've also added support for JQuery so developers less familiar with AngularJS can take advantage of Onsen UI, too.

Onsen UI also includes Onsen CSS Components, a free resource of UI templates with "theme roller" functionality. Developers can pick and choose, grab the code they need, and they're off and running. And they can create their own templates and submit to Onsen UI to be included with other templates available. 

Our [Monaca IDE] fully supports Onsen UI plugin.

## Browser Support

Onsen UI is tested with the following browsers and mobile OS.

 * Android 4.0.2+
 * iOS7+
 * Windows Phone 8.1+
 * Google Chrome
 * Safari

For versions earlier than 1.3.0, iOS 8.4+ is not supported. In order to use these versions with iOS 8.4+ the included FastClick library must be manually updated to the latest version.

## Demo

[Click here](http://onsen.io/guide/components.html) to see Onsen UI in action!

## What's Included

* [AngularJS](angularjs.org): for directives
* [Topcoat](topcoat.io): for fast UI css
* [HammerJS](http://eightmedia.github.io/hammer.js/): for touch, swipe handling
* [Font Awesome](http://fontawesome.io/): for icons

## Getting Started Using Templates

See the [Onsen UI Getting Started](http://onsen.io/getting_started/) page.

## Getting Started Using Monaca

See the [Onsen UI Getting Started Page] and scroll down to the Using Onsen UI with Monaca section. 

## Download the latest build

A new build is generated every time the code changes. It can be downloaded on [this page](http://onsen.io/download.html#latest-build).

Please use this with caution. However, we are very grateful if people try it out so we can find bugs and things to improve before the sharp releases.

## How to build

* Clone this repository

```bash
$ git clone https://github.com/OnsenUI/OnsenUI.git
```

* Open the terminal from OnsenUI directory

```bash
$ cd OnsenUI
```

* Install dependencies using [npm](http://nodejs.org/download/)

```bash
$ npm install
```

* Install gulp (globally)

```bash
$ [sudo] npm install -g gulp
```

* Type gulp to start building

```bash
$ gulp build
```

The files will be built and copied into **build**, **demo/lib/onsen/**, and **app/lib/onsen/** folder.

## Running Demo

```bash
$ npm install
$ [sudo] npm install -g gulp
$ gulp serve
```

* Then navigate your browser to [http://0.0.0.0:8000/demo/index.html](http://0.0.0.0:8000/demo/index.html)

## Running the test suite

Onsen UI has end-to-end testing using Protractor. Use the following command to run the tests:

```bash
$ npm install
$ gulp test
```

It will take some time the because it will download a stand-alone Selenium Server and a Chrome webdriver the first time it's executed.

To run a single test or a group of tests use the `--specs` parameter and provide a comma-separated list of spec files:

```bash
$ gulp test --specs test/e2e/lazyRepeat/scenarios.js
```

## Developing your app

Our [Monaca IDE] makes it super easy to create Onsen UI project, but if you want to use other IDEs, we provide project templates for you in the [`project-templates`](https://github.com/OnsenUI/project-templates) repository. You will see the instruction on how to run the project there.

## Documentation

See the current [Onsen UI docs](http://onsen.io/guide/overview.html).

## Developing Onsen UI

Run gulp task to develop Onsen UI itself with livereload.

    gulp serve

Access [http://0.0.0.0:8000/demo/index.html](http://0.0.0.0:8000/demo/index.html) and your code changes will be reloaded.

## Contributors

Please see the full [list of contributors](https://github.com/OnsenUI/OnsenUI/blob/master/CONTRIBUTORS.md).

## How to contribute

Please see our [document on contributing](https://github.com/OnsenUI/OnsenUI/blob/master/CONTRIBUTING.md).

## Getting support

If anything about Onsen UI is unclear, please ask a question on <a href="http://stackoverflow.com" target="_blank">Stackoverflow</a>, and tag it "onsen-ui".  An Onsen UI support engineer will answer it.

You can also join our [Gitter channel](https://gitter.im/OnsenUI/OnsenUI) if you want to talk about Onsen UI.

If you have any requests or comments regarding the development of Onsen UI, please feel free to direct them to the Twitter account (<a href="http://twitter.com/Onsen_UI" target="_blank">@Onsen_UI</a>).

[Onsen UI]:http://onsen.io/
[Onsen UI Getting Started Page]:http://onsen.io/getting_started/
[Monaca IDE]:http://monaca.mobi/
