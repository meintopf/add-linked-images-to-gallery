=== Add Linked Images To Gallery ===
Contributors: bbqiguana 
Donate link: http://www.bbqiguana.com/donate/
Tags: images, gallery, photobloggers
Requires at least: 2.7
Tested up to: 2.8.4
Stable tag: trunk

Makes local copies of all the linked images in a post, adding them as gallery attachments.

== Description ==

Extracts a list of IMG tags in the post, and saves copies of those images locally as gallery attachments on the post.

Particularly useful for photobloggers who update using the mail2blog Flickr API.   The plugin will saved the linked image file from Flickr locally.

There are currently no configuration options.  You just activate it and let it do its thing.

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
