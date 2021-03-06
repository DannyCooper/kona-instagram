=== Plugin Name ===
Contributors: gubbigubbi 	
Tags: gutenberg, instagram, instagram feed
Requires at least: 4.9.6
Tested up to: 4.9.8
Stable tag: 0.7
Requires PHP: 5.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Easily and instantly preview your instagram feed live within the new editor experience. Adjust settings as neededm such as the number of columns and the spacing. More features to come!

== Description ==

## Kona: Instagram Feed for Gutenberg
Easily and instantly preview your Instagram feed live within the new editor (Gutenberg) experience. Adjust settings as neededm such as the number of columns and the spacing. More features to come. 

###Wan't to see a feature?
###### Feel free to tweet and say 👋 at me [@RhysClay](https://twitter.com/rhysclay/)

== Installation ==

Firstly make sure that you have the Gutenberg plugin installed.

1. Install the Kona plugin either via the WordPress plugin directory, or by uploading the files to your web server (in the /wp-content/plugins/ directory).
1. Activate the Kona plugin through the 'Plugins' screen in WordPress
1. Get an Instagram Access Token: To do this login to instagram and [click here] (http://instagram.pixelunion.net/). Once you have a token, please paste it into the 'Instagram Access Token' setting.
1. Add the Kona block to your editor, paste the Access Token into the block settings.
1. Your Instagram feed will now show in the editor, adjust the settings to see how it will look before publishing.

== Frequently Asked Questions ==

= My feed isn't showing? =

Please make sure to add your Instagram access token the block settings. Once added you're feed should show instantly (well pretty fast at least).

= How about X feature? =

We will continue adding features as requested. If you have a killer idea for a feature submit a support request and we will see what we can do.
Note: we plan to release a premium version of the plugin which will likely receive new features first - this helps offset the cost of our development time.

= The feed looks funny in IE9 (Or other old browser)

This plugin is laid out using the new CSS Grid specification, we do not have plans to support older browsers as we believe they are holding back the web. However we can (if requested) release some code which you can add to your site's custom css in order to support certain browsers.

== Screenshots ==

1. Adding the Kona block to the editor.
1. Obtaining an Access Token from PixelUnion.
1. Adjusting the block settings.

== Changelog ==

= 0.7 =
* Added background color option

= 0.6.1 =
* Fixed bug where new feed would be stuck in loading mode.

= 0.6 =
* Added checks for caption before rendering caption. Added loading spinner. Added icon.

= 0.5 =
* Added a nice hover effect to images

= 0.4 =
* Added profile & option to show/hide profile.

= 0.3 =
* Updated caching system to include user ID so multiple feeds would work.
* Updated editor to notify user if the Insta API returns an error
* Removed links from editor images as these could be accidentaly clicked

= 0.2 =
* Added a caching system to reduce the number of requests the Insta API.

= 0.1 =
* First release.

== Coming Soon ==
* Ability to make all images the same size