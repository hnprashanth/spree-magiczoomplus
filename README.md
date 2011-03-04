SpreeMagiczoomplus
==================

Adds MagicZoomPlus to Spree store. http://www.magictoolbox.com/magiczoomplus/


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
