Search404
---------------------

Instead of showing a standard "404 Page not found", this module performs a search on the keywords in the URL.

CONTENTS OF THIS FILE
---------------------

 - Introduction
 - Tested
 - Known Issues
 - Special Thanks
 - Requirements
 - Installation
 - Coming From Drupal?
 - Usage
 - License
 - Credits
 - Maintainers

TESTED
-----

Working in Backdrop 1.3 for general usage, but this module extends other (not-ported-yet) modules, so some options are not available yet.

KNOWN ISSUES
---------------------

This module extends other (not-ported-yet) modules, so some options are not available yet.

SPECIAL THANKS
--------------

This module is sponsored by Zyxware Technologies. If you are interested in getting customization support or SEO support you can reach out to us at <http://www.zyxware.com> You can reach out to the developers of this module for paid support or customizations - contact zyxware at <http://www.zyxware.com/contact-us>

REQUIREMENTS
------------

search module enabled

INSTALLATION
------------

Install this module using the official Backdrop CMS instructions at https://backdropcms.org/guide/modules

Setup your options at: /admin/config/search/search404

COMING FROM DRUPAL?
-------------------

Nothing very much different.

PERMISSIONS
------------

none

USAGE
-----

Instead of showing a standard "404 Page not found", this module performs a search on the keywords in the URL, e.g. if a user goes to http://example.com/does/not/exist, this module will do a search for "does not exist" and shows the result of the search instead of the 404 page. This should help retain visitors coming in from old URLs linked from other sites or from search indices.

It also includes search engine keywords detections as well as regular expression based term filtering from the URL.

LICENSE
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.

CREDITS
-----------

Written by Lars Sehested Geisler <drupal@larsgeisler.dk>
Maintained by Zyxware, <http://www.zyxware.com/> <https://www.drupal.org/u/zyxware>
Some code from Steven (found at <http://drupal.org/node/12668>)
Originally maintained by Johan Forngren, <http://johan.forngren.com/>

MAINTAINERS
-----------

- seeking

Ported to Backdrop by:

- biolithic <https://github.com/biolithic>
