=== Image Quality ===
Contributors: gagan0123
Donate Link: PayPal.me/gagan0123
Tags: image, jpeg, compression, thumbnails, media
Requires at least: 2.8
Requires PHP: 5.6
Tested up to: 6.2.2
Stable tag: 1.5.2
License: GPLv2
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Lets you adjust the quality of image thumbnails that WordPress generates.

== Description ==

Sometimes you may want the images on your blog/site to be pixel perfect, while sometimes you may want them to be compressed to save space on the server.

This plugin allows you to select the quality of the thumbnail images generated by WordPress, as easy as that. Just go to Media Settings page and modify the Image Quality setting.

Plugin only works for new uploads, but in case you want to modify the thumbnails generated earlier, you can either use

[Regenerate Thumbnails](https://wordpress.org/plugins/regenerate-thumbnails/)

or if you are familiar with WP-CLI, then you can use this command to regenerate

`wp media regenerate`

P.S. It does not change the quality of the original image that you upload, 
but only changes the quality of the thumbnails WordPress generates from that image.

== Installation ==
1. Add the plugin's folder in the WordPress' plugin directory.
1. Activate the plugin.
1. Go to `Settings` > `Media` and set the Image Quality as needed.

== Screenshots ==
1. Adjust the setting by entering a number between 1 to 100 in Image Quality setting

== Changelog ==

= 1.5.2 =
* Tested compatibility with WordPress 5.6
* Corrected one escaping function from esc_attr to esc_url.

= 1.5.1 =
* Adhering to WordPress coding standards.
* Localization string correction.

= 1.5 =
* Better escaping of admin screen outputs.
* Added settings action link on the plugins page for easy access.
* Better documentation.

= 1.4 =
* Updated the changelog order.
* Updated WordPress' compatibility version.

= 1.3 =
* Removed an unused variable causing issues while debug mode is on.

= 1.2 =
* Another correction for localization.
* Fixing tags.

= 1.1 =
* Fixed text domain for localization.

= 1.0 =
* Initial Public Release.
