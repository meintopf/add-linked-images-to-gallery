=== Add Linked Images To Gallery ===
Contributors: bbqiguana 
Donate link: http://www.bbqiguana.com/donate/
Tags: images, gallery, photobloggers, attachments, photo, links, external, photographers, Flickr
Requires at least: 2.7
Tested up to: 2.9
Stable tag: 0.7

Makes local copies of all the linked images in a post, adding them as gallery attachments.

== Description ==

Create local copies of external images in the src attribute of img tags.  This plugin extracts a list of IMG tags in the post, saves copies of those images locally as gallery attachments on the post.

= Features =
* Finds all external images linked in the SRC attribute of IMG tags and makes local copies of those images
* Allows the SRC to be updated to point to those local copies
* Can be applied to posts in all categories, or only those selected
* Can be applied to all authors, or only selected authors

Administrator has the option to replace the external src with the url of the local copy. Another option allows the plugin to be applied to all external images, or only to those on Flickr.

This plugin is particularly useful for photobloggers, especially those who update using the mail2blog Flickr API.   The plugin will saved the linked image file from Flickr locally.

= Planned features: =
* Add internationalization support
* Integrate with Flickr API in order to allow always downloading the original image size regardless of which is linked
* Additional options to allow running the plugin only for specific users or categories

== Installation ==

1. Download the External Image Loader zip file.
2. Extract the files to your WordPress plugins directory.
3. Activate the plugin via the WordPress Plugins tab.

== Frequently Asked Questions ==

none

== Screenshots ==

none

== Changelog ==

= 0.7 =
* Fixes a syntax error in creating the new attachment

= 0.6 =
* Suppresses safe_mode warnings from CURL
* Adds support for WordPress 2.9

= 0.5 =
* Fixes a bug that cause all img tags to be rewritten as the last matched image.

= 0.4 =
* Option added to option panel allowing the plugin to run only on posts in specific categories
* Option added to option panel allowing the plugin to run only on posts by specific authors

= 0.3 =
* Improved pattern matching for images
* 404 errors not processed
* Flickr "image-not-found" jpg not processed
* Improved local file naming
* Replace feature was replacing URL in entire text. Now only replaces in IMG src.
* Added feedback when options are saved.

= 0.2 =
* Added options panel
* User can apply plugin to all external images or choose only to apply to Flickr
* User can choose to either mark images by custom tag, or to replace image source
* Custom tag name is user-definable
* Improved regular expression matching

= 0.1 =
* Initial version.
