Welcome to John's Expression Engine Global Config
=================================================

This repository was created to host my Expression Engine global config file in hopes to manage my projects better, but also to give back to the community.

It is a fork of Leevi Graham <http://leevigraham.com> and Newism's work and I hope to make sensible updates/changes to it.

Disclaimer
----------

I am not a professional/full-time Expression Engine developer so I probably won't be keeping this repository up to date with each release of EE.  I also am not a full-time CMS developer so I do not have a ton of opportunities to work on EE or CMS driven sites.  I do have a ton of PHP and Ruby/Rails experience and I used to be a "CMS guy", but it's mostly limited to Drupal.

The updates to Leevi's config file is mostly influenced by @bitmanic and my experience with Ruby on Rails.

Please let me know if you use this file and if you have any suggestions/changes you'd like to make.  I would love to accept patches and changes from the EE community.

Organization
------------

The directory structure that I'm planning to follow is to have the EE system and template folders be private and only have public assets and themes be public.

<pre>
ROOT
+--config
+   +--config.php
+   +--config.php.example
+--public
+   +--.htaccess
+   +--index.php
+   +--images
+   +--themes
+--system
+--templates
+--vendor
    +--add-ons
    +--themes
</pre>