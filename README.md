SpreeMagiczoomplus
==================

Adds MagicZoomPlus to Spree store. http://www.magictoolbox.com/magiczoomplus/

This extension is better than Spree Zoom Photos (http://github.com/eliotsykes/spree-zoom-photos) since it gives complete image handling control to Magic Zoom.
I personally had problems in handling multiple product images while using Spree Zoom Photos PLUS this extension works with latest Spree.

Features
========

* Zoom into product images.
* Multiple image handling. (see multiple image example here http://www.magictoolbox.com/magiczoomplus/examples/)
* Changes product image by hovering on thumbnail.
* Fancybox like Click to enlarge in zoom view.
* Navigate between images in enlarged view using next/previous buttons.


Installation
============

Add Spree-MagicZoomPlus to your Gemfile.

    gem "spree_magiczoomplus", :git => 'git://github.com/hnprashanth/Spree-MagicZoomPlus.git'

Update your bundle

    bundle install

Run Install

    rake spree_magiczoomplus:install

And you are good to go :-)
To set options to zoom edit /public/javascripts/zoomoptions.js as instructed in http://www.magictoolbox.com/magiczoomplus/integration/


Copyright (c) 2011 SpreeMagiczoomplus, released under the New BSD License
