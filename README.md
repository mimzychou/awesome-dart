Awesome Dart [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
============

A curated list of Dart code and resources, inspired by awesome lists.

want to contribute, please read [contribution](/CONTRIBUTING.md). Thank you !

## Contents
- [Applications written in Dart](#applications-written-in-dart)
- [Development Tools](#development-tools)
- [Libraries](#libraries)
  - [Animation](#animation)
  - [Clint Frameworks](#clint-frameworks)
  - [Clint Library](#clint-library)
  - [Command line](#command-line)
  - [Crypto](#crypto)
  - [Database](#database)
  - [Encoding](#encoding)
  - [Game](#game)
  - [Graphics](#graphics)
  - [Image](#image)
  - [Low Level](#low-level )
  - [ORM](#orm)
  - [Parsers](#parsers)
  - [Serializer](#serializer)
  - [Server Frameworks](#server-frameworks)
  - [Template](#template)
  - [Utility](#utility)
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
* [watcher](https://github.com/dart-lang/watcher) - A file system watcher library for Dart.[<img src="https://travis-ci.org/dart-lang/watcher.svg?branch=master">](https://travis-ci.org/dart-lang/watcher)
* [dart2js_info](https://github.com/dart-lang/dart2js_info)- Model of the data produced by dart2js with --dump-info, and tools that process the information.[<img src="https://travis-ci.org/dart-lang/dart2js_info.svg?branch=master">](https://travis-ci.org/dart-lang/dart2js_info)
* [linter](https://github.com/dart-lang/linter) - Style linter for Dart.[<img src="https://travis-ci.org/dart-lang/linter.svg?branch=master">](https://travis-ci.org/dart-lang/linter)
* [intl](https://github.com/dart-lang/intl) - Internationalization and localization support.[<img src="https://travis-ci.org/dart-lang/intl.svg?branch=master">](https://travis-ci.org/dart-lang/intl)
* [dart_style](https://github.com/dart-lang/dart_style) - An opinionated formatter/linter for Dart code.[<img src="https://travis-ci.org/dart-lang/dart_style.svg?branch=master">](https://travis-ci.org/dart-lang/dart_style)
* [source_gen](https://github.com/dart-lang/source_gen) - Automatic source code generation for Dart.[<img src="https://travis-ci.org/dart-lang/source_gen.svg?branch=master">](https://travis-ci.org/dart-lang/source_gen)
* [dartdoc](https://github.com/dart-lang/dartdoc) - API documentation tool for Dart.[<img src="https://travis-ci.org/dart-lang/dartdoc.svg?branch=master">](https://travis-ci.org/dart-lang/dartdoc)
* [ts2dart](https://github.com/angular/ts2dart) - ts2dart TypeScript to Dart transpiler.[<img src="https://travis-ci.org/angular/ts2dart.svg?branch=master">](https://travis-ci.org/angular/ts2dart)

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

* **Workflow**

  * [grinder](https://github.com/google/grinder.dart)- Dart workflows, automated.[<img src="https://travis-ci.org/google/grinder.dart.svg?branch=master">](https://travis-ci.org/google/grinder.dart)

## Libraries

#### Animation

* [Universal Tween Engine](https://github.com/xaguzman/tween-engine-dart) - A port of the original java Universal Tween Engine created by Aurelien Ribbon.[<img src="https://travis-ci.org/xaguzman/tween-engine-dart.svg?branch=master">](https://travis-ci.org/xaguzman/tween-engine-dart)

#### Clint Frameworks

* [Angular2](https://github.com/dart-lang/angular2) - Angular is a development platform for building mobile and desktop web applications.[<img src="https://travis-ci.org/dart-lang/angular2.svg?branch=master">](https://travis-ci.org/dart-lang/angular2)
* [Polymer](https://github.com/dart-lang/polymer-dart) - Polymer support for Dart [<img src="https://travis-ci.org/dart-lang/polymer-dart.svg?branch=master">](https://travis-ci.org/dart-lang/polymer-dart)
* [ng_bootstrap](https://github.com/dart-league/ng_bootstrap) - A bootstrap 4 and angular 2 package for dartlang.
* [route.dart](https://github.com/angular/route.dart) -Route is a client routing library for Dart that helps make building single-page web apps.[<img src="https://travis-ci.org/angular/route.dart.svg?branch=master">](https://travis-ci.org/angular/route.dart)

#### Clint Library

* [dart-service-worker](https://github.com/sladage/dart-service-worker) - Service Worker library for Dart.


#### Command line

* [tuneup](https://github.com/google/tuneup.dart) - A command-line tool to manipulate and inspect your Dart projects.
[<img src="https://travis-ci.org/google/tuneup.dart.svg?branch=master">](https://travis-ci.org/google/tuneup.dart)

#### Crypto

* [Crypto](https://github.com/dart-lang/crypto) - A set of cryptographic functions implemented in pure Dart. [<img src="https://travis-ci.org/dart-lang/crypto.svg?branch=master">](https://travis-ci.org/dart-lang/crypto)

#### Database

* [mongo_dart](https://github.com/mongo-dart/mongo_dart) - Mongo_dart: MongoDB driver for Dart programming language.[<img src="https://travis-ci.org/mongo-dart/mongo_dart.svg?branch=master">](https://travis-ci.org/mongo-dart/mongo_dart)
* [Dartabase](https://github.com/HannesRammer/Dartabase) - Database (Rails like) migration and model tool for MYSQL and PGSQL in Dart without having to write SQL.[<img src="https://travis-ci.org/dart-bridge/framework.svg?branch=master">](https://travis-ci.org/HannesRammer/Dartabase)
* [sqljocky](https://github.com/jamesots/sqljocky) - MySQL Connector for Dart.
* [PostgreSQL](https://github.com/xxgreg/dart_postgresql) - Dart Postgresql database library.[<img src="https://travis-ci.org/xxgreg/dart_postgresql.svg?branch=master">](https://travis-ci.org/xxgreg/dart_postgresql)

#### Encoding

* [Archive](https://pub.dartlang.org/packages/archive) - Dart library to encode and decode various archive and compression formats, such as Zip and Tar.

#### Game

* [StageXL](https://github.com/bp74/StageXL) - A fast and universal 2D rendering engine for HTML5 and Dart.[<img src="https://travis-ci.org/bp74/StageXL.svg?branch=master">](https://travis-ci.org/bp74/StageXL/branches)
* [DartRocket](https://github.com/StrykerKKD/dartrocket) - HTML5 game framework made with Dart and StageXL.
* [Pixi Dart](https://github.com/FedeOmoto/pixi) - A port of the pixi.js rendering engine.
* [Ranger](https://github.com/wdevore/Ranger-Dart) - Game engine written in Dart.

#### Graphics

* [dart-gl](https://github.com/google/dart-gl) - OpenGL ES 2.0 Dart Native Extension.[<img src="https://travis-ci.org/google/dart-gl.svg?branch=master">](https://travis-ci.org/google/dart-gl)
* [dart-glfw](https://github.com/google/dart-glfw) - Dart bindings for GLFW, a multiplatform library for creating windows with OpenGL contexts.[<img src="https://travis-ci.org/google/dart-glfw.svg?branch=master">](https://travis-ci.org/google/dart-glfw)
* [bagl](https://github.com/RSSchermer/bagl.dart) - BaGL is a low-level abstraction on top of WebGL. It aims to provide a simpler, safer and more declarative drawing alternative to plain WebGL.[<img src="https://travis-ci.org/RSSchermer/bagl.dart.svg?branch=master">](https://travis-ci.org/RSSchermer/bagl.dart)
* [cairodart](https://github.com/alexander-dembinsky/cairodart) - Cairo bindings for Dart.[<img src="https://travis-ci.org/alexander-dembinsky/cairodart.svg?branch=master">](https://travis-ci.org/alexander-dembinsky/cairodart)
* [ThreeDart](https://github.com/Grant-Nelson/ThreeDart) - 3D graphical rendering tool for websites writing in Dart.
* [dartgl](https://pub.dartlang.org/packages/dartgl)

#### Image

* [image](https://github.com/brendan-duncan/image) - Dart library for decoding/encoding image formats, and image processing.

#### Low Level

* [dart2asm](https://github.com/thosakwe/dart2asm) - Compiles a very limited subset of Dart into x86 Assembly.
* [kernel](https://github.com/dart-lang/kernel) - Dart IR (Intermediate Representation).[<img src="https://travis-ci.org/dart-lang/kernel.svg?branch=master">](https://travis-ci.org/dart-lang/kernel)

#### ORM

* [DartORM](https://github.com/ustims/DartORM) - Database ORM for dart language for MySQL ,MongoDB,PostgreSQL.[<img src="https://travis-ci.org/dart-lang/markdown.svg?branch=master">](https://travis-ci.org/dart-lang/markdown)


#### Parsers

* [html](https://github.com/dart-lang/html) - Dart port of html5lib. For parsing HTML/HTML5 with Dart. Works in the client and on the server. [<img src="https://travis-ci.org/dart-lang/html.svg?branch=master">](https://travis-ci.org/dart-lang/html)
* [markdown](https://github.com/dart-lang/markdown) - A Dart markdown library.[<img src="https://travis-ci.org/dart-lang/markdown.svg?branch=master">](https://travis-ci.org/dart-lang/markdown)
* [PetitParser](https://github.com/petitparser/dart-petitparser) - Dynamic Grammars in Dart.[<img src="https://travis-ci.org/petitparser/dart-petitparser.svg?branch=master">](https://travis-ci.org/petitparser/dart-petitparser)
* [XML](https://github.com/renggli/dart-xml) - Lightweight library for parsing, traversing, and querying XML in Dart.[<img src="https://travis-ci.org/renggli/dart-xml.svg?branch=master">](https://travis-ci.org/renggli/dart-xml)
* [yaml](https://github.com/dart-lang/yaml) - A Dart YAML parser. [<img src="https://travis-ci.org/dart-lang/yaml.svg?branch=master">](https://travis-ci.org/dart-lang/yaml)
* [args](https://github.com/dart-lang/args) - A command-line argument parsing library for Dart. [<img src="https://travis-ci.org/dart-lang/args.svg?branch=master">](https://travis-ci.org/dart-lang/args)

#### Serializer

* [serialization](https://github.com/google/serialization.dart) - A serialization library for Dart.[<img src="https://travis-ci.org/google/serialization.dart.svg?branch=master">](https://travis-ci.org/google/serialization.dart)
* [serializer](https://github.com/dartsome/serializer) - Serialize and Deserialize Dart Object with reflectable.[<img src="https://travis-ci.org/dartsome/serializer.svg?branch=master">](https://travis-ci.org/dartsome/serializer)


#### Server Frameworks

* [angel](https://github.com/angel-dart/angel) - An easily-extensible web server framework in Dart.
* [Redstone](https://github.com/redstone-dart/redstone) - Redstone is a server-side, metadata driven micro-framework for Dart.[<img src="https://travis-ci.org/redstone-dart/redstone.svg?branch=v0.6">](https://travis-ci.org/redstone-dart/redstone)
* [Start](https://github.com/lvivski/start) - Sinatra inspired web framework to serve static files, handle dynamic requests, websockets and create JSON responses.
* [Express](https://github.com/dartist/express) - A simple, thin expressjs inspired layer around Dart's primitive HttpServer APIs.[<img src="https://travis-ci.org/dartist/express.svg?branch=master">](https://travis-ci.org/dartist/express)
* [Shelf](https://github.com/dart-lang/shelf) - Web server middleware for Dart.[<img src="https://travis-ci.org/dart-lang/shelf.svg?branch=master">](https://travis-ci.org/dart-lang/shelf)
* [Force](https://github.com/ForceUniverse/dart-force) - A real time web framework, embracing websockets, making communication even better. [<img src="https://travis-ci.org/ForceUniverse/dart-force.svg?branch=master">](https://travis-ci.org/ForceUniverse/dart-force)
* [Vane](https://github.com/Scorpiion/Vane) - Framework with built-in server runtime environment and middleware system
* [Stream](https://github.com/rikulo/stream) - Lightweight web server with request routing, filtering, template engine, WebSocket, MVC design pattern, and file-based static resources
* [stagehand](https://github.com/google/stagehand) - Dart project generator - web apps, console apps, servers, and more.  [<img src="https://travis-ci.org/google/stagehand.svg?branch=master">](https://travis-ci.org/google/stagehand)
* [dart-bridge](https://github.com/dart-bridge/framework) - An extensible end-to-end framework for Dart. [<img src="https://travis-ci.org/dart-bridge/framework.svg?branch=master">](https://travis-ci.org/dart-bridge/framework)
* [hop](https://github.com/kevmoo/hop) - A Dart framework for reusable tasks. [<img src="https://travis-ci.org/kevmoo/hop.svg?branch=master">](https://travis-ci.org/kevmoo/hop)

#### Template

* [mustache4dart](https://github.com/valotas/mustache4dart) - mustache implementation for Dart.[<img src="https://travis-ci.org/valotas/mustache4dart.svg?branch=master">](https://travis-ci.org/valotas/mustache4dart)

#### Utility

* [collection](https://github.com/dart-lang/collection) - contains a number of separate libraries with utility functions and classes that makes working with collections easier.[<img src="https://travis-ci.org/dart-lang/collection.svg?branch=master">](https://travis-ci.org/dart-lang/collection)
* [quiver-dart](https://github.com/google/quiver-dart) - A set of utility libraries for Dart.[<img src="https://travis-ci.org/google/quiver-dart.svg?branch=master">](https://travis-ci.org/google/quiver-dart)
* [reflectable](https://github.com/dart-lang/reflectable) - Reflectable is a Dart library that allows programmers to eliminate certain usages of dynamic reflection by specialization of reflective code to an equivalent implementation using only static techniques. [<img src="https://travis-ci.org/dart-lang/reflectable.svg?branch=master">](https://travis-ci.org/dart-lang/reflectable)
* [Archive](https://pub.dartlang.org/packages/archive) - Dart library to encode and decode various archive and compression formats, such as Zip and Tar.
* [serialization](https://github.com/google/serialization.dart) - A serialization library for Dart.[<img src="https://travis-ci.org/google/serialization.dart.svg?branch=master">](https://travis-ci.org/google/serialization.dart)
* [commons](https://github.com/rikulo/commons) - Common reusable Dart classes and utilities.

#### Validation

* [Constrain](https://pub.dartlang.org/packages/constrain) - Provides a constraint based Validation library inspired by Java Bean Validation but leveraging the superior language capabilities of Dart.


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
  * [IOT: Dartino](https://dartino.org/getting-started/)


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
