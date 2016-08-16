Awesome Dart [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
============

A curated list of Dart code and resources, inspired by awesome lists.

want to contribute, please read [contribution](/CONTRIBUTING.md). Thank you !

## Contents
- [Applications written in Dart](#applications-written-in-dart)
- [Development Tools](#development-tools)
- [Libraries](#libraries)
  - [Algorithms](#algorithms)
  - [Animation](#animation)
  - [Client App Frameworks](#client-app-frameworks)
  - [Crypto](#crypto)
  - [Database](#database)
  - [Dependency Injection](#dependency-injection)
  - [Game Development](#game-development)
  - [Image](#image)
  - [ORM](#orm)
  - [Parsers](#parsers)
  - [Server Frameworks](#server-frameworks)
  - [Template](#template)
  - [Utilities](#utilities)
  - [Validation](#validation)
- [Resources](#resources)
- [License](#license)

----

## Applications-written-in-Dart


## Development-Tools

* [Pub](https://github.com/dart-lang/pub) - Pub is Dart package manager.[<img src="https://travis-ci.org/dart-lang/pub.svg?branch=master">](https://travis-ci.org/dart-lang/pub)
* [Stagehand](https://github.com/google/stagehand) - A project scaffolding generator, inspired by tools like Web Starter Kit and Yeoman.[<img src="https://travis-ci.org/google/stagehand.svg?branch=master">](https://travis-ci.org/google/stagehand)
* [Crossdart](http://crossdart.info) - Cross-reference of Dart packages.[<img src="https://travis-ci.org/astashov/crossdart.svg?branch=master">](https://travis-ci.org/astashov/crossdart)
* [Crossdart Github Chrome Extension](https://github.com/astashov/crossdart-chrome-extension) - Adds "Go to declaration" and "Find Usages" functionality to your Dart projects on Github [<img src="https://travis-ci.org/astashov/crossdart-chrome-extension.svg?branch=master">](https://travis-ci.org/astashov/crossdart-chrome-extension)
* [gulp-dart](https://github.com/agudulin/gulp-dart) - A gulp plugin for compiling Dart code to JavaScript using dart2js.[<img src="https://travis-ci.org/agudulin/gulp-dart.svg?branch=master">](https://travis-ci.org/agudulin/gulp-dart)
* [dev_compiler](https://github.com/dart-lang/dev_compiler) - Dart to JavaScript compiler designed to create idiomatic, readable JavaScript output.[<img src="https://travis-ci.org/dart-lang/dev_compiler.svg?branch=master">](https://travis-ci.org/dart-lang/dev_compiler)
* [markdown](https://github.com/dart-lang/markdown) - A Dart markdown library[<img src="https://travis-ci.org/dart-lang/markdown.svg?branch=master">](https://travis-ci.org/dart-lang/markdown)
* [watcher](https://github.com/dart-lang/watcher) - A file system watcher library for Dart.[<img src="https://travis-ci.org/dart-lang/watcher.svg?branch=master">](https://travis-ci.org/dart-lang/watcher)
* [dart2js_info](https://github.com/dart-lang/dart2js_info)- Model of the data produced by dart2js with --dump-info, and tools that process the information.[<img src="https://travis-ci.org/dart-lang/dart2js_info.svg?branch=master">](https://travis-ci.org/dart-lang/dart2js_info)
* [linter](https://github.com/dart-lang/linter) - Style linter for Dart.[<img src="https://travis-ci.org/dart-lang/linter.svg?branch=master">](https://travis-ci.org/dart-lang/linter)
* [intl](https://github.com/dart-lang/intl) - Internationalization and localization support.[<img src="https://travis-ci.org/dart-lang/intl.svg?branch=master">](https://travis-ci.org/dart-lang/intl)
* [dart_style](https://github.com/dart-lang/dart_style) - An opinionated formatter/linter for Dart code.[<img src="https://travis-ci.org/dart-lang/dart_style.svg?branch=master">](https://travis-ci.org/dart-lang/dart_style)
* [source_gen](https://github.com/dart-lang/source_gen) - Automatic source code generation for Dart.[<img src="https://travis-ci.org/dart-lang/source_gen.svg?branch=master">](https://travis-ci.org/dart-lang/source_gen) 
* [dartdoc](https://github.com/dart-lang/dartdoc) - API documentation tool for Dart.[<img src="https://travis-ci.org/dart-lang/dartdoc.svg?branch=master">](https://travis-ci.org/dart-lang/dartdoc) 
* [args](https://github.com/dart-lang/args) - A command-line argument parsing library for Dart. [<img src="https://travis-ci.org/dart-lang/args.svg?branch=master">](https://travis-ci.org/dart-lang/args) 
* [yaml](https://github.com/dart-lang/yaml) - A Dart YAML parser. [<img src="https://travis-ci.org/dart-lang/yaml.svg?branch=master">](https://travis-ci.org/dart-lang/yaml) 


* **Build System**

  * [build](https://github.com/dart-lang/build) - A build system for Dart [<img src="https://travis-ci.org/dart-lang/build.svg?branch=master">](https://travis-ci.org/dart-lang/build)
  * [barback](https://github.com/dart-lang/barback) - An asset build system for Dart.[<img src="https://travis-ci.org/dart-lang/barback.svg?branch=master">](https://travis-ci.org/dart-lang/barback)

* **IDEs**  : See also [Dart Tools](https://www.dartlang.org/tools).

  * [Sublime Text](https://github.com/guillermooo/dart-sublime-bundle) - Sublime Text 3 Dart Package[<img src="https://travis-ci.org/guillermooo/dart-sublime-bundle.svg?branch=master">](https://travis-ci.org/guillermooo/dart-sublime-bundle)
  * [Emacs](https://github.com/nex3/dart-mode) - An Emacs mode for the Dart language[<img src="https://travis-ci.org/nex3/dart-mode.svg?branch=master">](https://travis-ci.org/nex3/dart-mode)
  * [Vim](https://github.com/dart-lang/dart-vim-plugin) - Dart for Vim[<img src="https://travis-ci.org/dart-lang/dart-vim-plugin.svg?branch=master">](https://travis-ci.org/dart-lang/dart-vim-plugin)
  *  Atom
     * [Atom-dart](https://github.com/dart-atom/dartlang) - Dart support for Atom.[<img src="https://travis-ci.org/dart-atom/dartlang.svg?branch=master">](https://travis-ci.org/dart-atom/dartlang)
     * [Atom-flutter](https://github.com/dart-atom/dartlang) - Dart-flutter support for Atom.[<img src="https://travis-ci.org/flutter/atom-flutter.svg?branch=master">](https://travis-ci.org/flutter/atom-flutter)

* **Testing**

  * [Test](https://pub.dartlang.org/packages/test) - A library for writing unit tests in Dart.[<img src="https://travis-ci.org/dart-lang/test.svg?branch=travis">](https://travis-ci.org/dart-lang/test)

* **Logging**

  * [logging](https://github.com/dart-lang/logging) - A Dart package for debug and error logging. [<img src="https://travis-ci.org/dart-lang/logging.svg?branch=master">](https://travis-ci.org/dart-lang/logging)

## Libraries

#### Animation

* [Universal Tween Engine](https://github.com/xaguzman/tween-engine-dart) - A port of the original java Universal Tween Engine created by Aurelien Ribbon.[<img src="https://travis-ci.org/xaguzman/tween-engine-dart.svg?branch=master">](https://travis-ci.org/xaguzman/tween-engine-dart)

#### Algorithms


#### Client App Frameworks

* [Angular2](https://github.com/dart-lang/angular2) - Angular is a development platform for building mobile and desktop web applications.[<img src="https://travis-ci.org/dart-lang/angular2.svg?branch=master">](https://travis-ci.org/dart-lang/angular2)
* [Polymer](https://github.com/dart-lang/polymer-dart) - Polymer support for Dart [<img src="https://travis-ci.org/dart-lang/polymer-dart.svg?branch=master">](https://travis-ci.org/dart-lang/polymer-dart)

#### Crypto

* [Crypto](https://github.com/dart-lang/crypto) - A set of cryptographic functions implemented in pure Dart. [<img src="https://travis-ci.org/dart-lang/crypto.svg?branch=master">](https://travis-ci.org/dart-lang/crypto)

#### Database

* [SQLJockey](https://github.com/jamesots/sqljocky) - MySQL connector.
* [PostgreSQL](https://github.com/xxgreg/dart_postgresql) - PostgreSQL database driver
* [dartabase_model](https://pub.dartlang.org/packages/dartabase_model) - Serverside Database Object Models for simple data manipulation using MySQL/PGSQL without having to write SQL
* [dartabase_migration](https://pub.dartlang.org/packages/dartabase_migration) - Serverside Database migration for simple version controlled database structure manipulation using MySQL/PGSQL without having to write SQL

#### Dependency Injection

* [DI](https://github.com/angular/di.dart) - Dependency Injection framework by Angular

#### Game Development

* [StageXL](http://www.stagexl.org/) - StageXL offers an easy to use and complete API (based on the Flash API) for impressive 2D content like games and other rich applications.
* [DartRocket](https://github.com/StrykerKKD/dartrocket) - DartRocket is a HTML5 game framework written in Dart and which uses the StageXL rendering engine.
* [Pixi Dart](https://github.com/FedeOmoto/pixi) - A port of the pixi.js rendering engine.
* [Ranger](https://github.com/wdevore/Ranger-Dart) - A game engine centered around HTML5 Canvas and a scene graph.

#### Image

* [image](https://github.com/brendan-duncan/image) - Provides server and web apps the ability to load, manipulate, and save images with various image file formats including PNG, JPEG, GIF, WebP, TIFF, TGA, PSD, PVR, and OpenEXR.

#### ORM

* [Objectory](https://github.com/vadimtsushko/objectory) - Objectory provides typed, checked environment to model, save and query data persisted on MongoDb.

#### Parsers

* [html](https://pub.dartlang.org/packages/html) - A library for working with HTML documents. Previously known as html5lib.
* [markdown](https://github.com/dart-lang/markdown) - Parse markdown into HTML on both the client and server.
* [PetitParser](https://github.com/petitparser/dart-petitparser) - PetitParser combines ideas from scannerless parsing, parser combinators, parsing expression grammars and packrat parsers to model grammars and parsers as objects that can be reconfigured dynamically.
* [XML](https://pub.dartlang.org/packages/xml) - A lightweight library for parsing, traversing, querying and building XML documents.
* [xmlstream](https://pub.dartlang.org/packages/xml) - A streaming event-based XML Parser.
* [YAML](https://pub.dartlang.org/packages/yaml) - A parser for YAML.

#### Server Frameworks

* [Redstone](https://github.com/redstone-dart/redstone) - Redstone is a server-side, metadata driven micro-framework for Dart.[<img src="https://travis-ci.org/redstone-dart/redstone.svg?branch=v0.6">](https://travis-ci.org/redstone-dart/redstone)
* [Start](https://github.com/lvivski/start) - Sinatra inspired web framework to serve static files, handle dynamic requests, websockets and create JSON responses.
* [Express](https://github.com/dartist/express) - A simple, thin expressjs inspired layer around Dart's primitive HttpServer APIs.
* [Shelf](https://github.com/dart-lang/shelf) - Web server middleware for Dart.[<img src="https://travis-ci.org/dart-lang/shelf.svg?branch=master">](https://travis-ci.org/dart-lang/shelf)
* [Force](https://github.com/ForceUniverse/dart-force) - A real time web framework, embracing websockets, making communication even better
* [Vane](https://github.com/Scorpiion/Vane) - Framework with built-in server runtime environment and middleware system
* [Rikulo Stream](https://github.com/rikulo/stream) - Lightweight web server with request routing, filtering, template engine, WebSocket, MVC design pattern, and file-based static resources

#### Template

* [mustache4dart](https://github.com/valotas/mustache4dart) - A simple implementation of Mustache.
* [jaded](https://github.com/dartist/jaded) - Port of the excellent Jade view engine.

#### Utilities

* [Flutter](https://github.com/flutter/engine) - Flutter is a new way to build high-performance, cross-platform mobile apps, allowing you to write applications for Android and iOS.
* [Quiver](https://github.com/google/quiver-dart) - A set of utility libraries that makes using many libraries easier and more convenient, or adds additional functionality.
* [route_hierarchical](https://github.com/angular/route.dart) - Route is a client routing library for Dart that helps make building single-page web apps.
* [Archive](https://pub.dartlang.org/packages/archive) - A library to encode and decode various archive and compression formats.
* [Frappe](https://pub.dartlang.org/packages/frappe) - A functional reactive programming library for Dart. Frappé extends the functionality of Dart's streams, and introduces new concepts like properties/signals.

#### Validation

* [Constrain](https://pub.dartlang.org/packages/constrain) - Provides a constraint based Validation library inspired by Java Bean Validation but leveraging the superior language capabilities of Dart.
* [validator.dart](https://github.com/karan/validator.dart) - String validation and sanitization for Dart.


## Resources

*  Learning

  * [DartPad](https://dartpad.dartlang.org/)
  * [A Tour of the Dart Language](https://www.dartlang.org/guides/language/language-tour)-and-[A Tour of the Dart Libraries](https://www.dartlang.org/guides/libraries/library-tour)  
  * [samples](https://www.dartlang.org/samples)-and-[dart-by-example](https://www.dartlang.org/dart-vm/dart-by-example)
  * [Hello Dart](http://code.makery.ch/library/hello-dart/) - A playful introduction to Dart.
  * [Effective Dart](https://www.dartlang.org/guides/language/effective-dart)
  * [Dart Language Specification](http://www.ecma-international.org/publications/standards/Ecma-408-arch.htm)
  * [Books](https://www.dartlang.org/resources/books)
  * [dart-academy](https://dart.academy/)

* Benchmarks

  * [The Computer Language Benchmarks Game ](http://benchmarksgame.alioth.debian.org/)
  
* Community

  * [StackOverflow](http://stackoverflow.com/tags/dart)
  * [reddit](https://www.reddit.com/r/dartlang)
  * [dartosphere](https://www.dartosphere.org/)
  * [Google+](https://plus.google.com/+dartlang)-and-[Dartisans](https://plus.google.com/communities/114566943291919232850)
  * [Twitter](https://twitter.com/dart_lang)

* Dart in Everywhere

  * [Web: webdev](https://webdev.dartlang.org/guides/get-started)
  * [Serve: Dart-VM](https://www.dartlang.org/tutorials/dart-vm/get-started)
  * [Mobile: Flutter](https://flutter.io/getting-started/)
  * [Iot: Dartino](https://dartino.org/getting-started/)


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
