travis-ci actionscript-demo
=====
[![Build Status](https://travis-ci.org/Larusso/travis-CI-actionscript-demo.png?branch=master)](https://travis-ci.org/Larusso/travis-CI-actionscript-demo)

A simple demo that demonstrates a way to unit test action scrip applications with [travis-ci](http://travis-ci.org)

The demo runs a osx travis environment to start the flash player. The flash player will be downloaded from the adobe website at runtime. See travis.yml for more information. All dependencies (flex sdk, flex unit) will be resolved by maven with [flex-mojos](http://code.google.com/p/flex-mojos/)


