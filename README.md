Node.js - npm-latest
====================

Quickly find the latest version of a package in `npm`.

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)


Why?
----

I often forget which package version I need to put as a dependency in my packages. Running `npm info [package]` and then scrolling up scanning JSON became annoying.

**Update 2015-03-29:**

Support config registry in `~/.npmrc` file，more on [registry-url](https://github.com/sindresorhus/registry-url)


**Update:**

Thanks to [@timoxley](https://github.com/timoxley) for pointing out that a very viable alternative would be to just run:

    npm install --save packagename@latest

It has the added bonus of updating your package.json file as well.



Installation
------------

    npm install -g npm-latest



Example
------

    npm-latest express

output:

      express:

        latest: 3.0.0rc2
        last updated: Fri Aug 03 2012 15:33:05 GMT-0500 (CDT)
        author: TJ Holowaychuk
        repo: git://github.com/visionmedia/express
        description: Sinatra inspired web development framework



License
-------

(MIT License)

Copyright 2012-2015, JP Richardson <jprichardson@gmail.com>

