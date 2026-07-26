=== Speed Up - JavaScript To Footer ===
Contributors: nigro.simone
Donate link: http://paypal.me/snwp
Tags: javascript to footer, render blocking, preload scripts, page speed, performance
Requires at least: 6.0
Requires PHP: 7.0
Tested up to: 7.0
Stable tag: 1.0.14
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Move all the possible JavaScript files from head to footer and improve page load times.

== Description ==

This small plugin (2 Kb) moves JavaScript to the footer and improve page load times.
Note: this only works if your other plugins and theme add the JavaScripts correctly.

Configurations are not required! You just have to install it and after the plugin does it all, none further action it's required. 

== Installation ==

1. Upload the complete `javascript-to-footer` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Changelog ==

= 1.0.14 =
* Documentation: explain why the plugin does not use the defer strategy added in WordPress 6.3, and how to use it directly if you prefer

= 1.0.13 =
* Fix a fatal error on WordPress older than 4.2: the plugin uses wp_scripts(), available since 4.2, but declared compatibility with 3.5
* Escape the script URL in the generated preload tag
* Skip preloading scripts registered for Internet Explorer, which no browser in use would run
* Declare minimum requirements: WordPress 6.0 and PHP 7.0

= 1.0.12 =
* Tested up to Wordpress 7.0

= 1.0.11 =
* Tested up to Wordpress 6.0

= 1.0.10 =
* Tested up to Wordpress 5.9

= 1.0.9 =
* Tested up to Wordpress 5.7

= 1.0.8 =
* Tested up to Wordpress 5.5

= 1.0.7 =
* Readme

= 1.0.6 =
* Tested up to Wordpress 5.3

= 1.0.5 =
* Tested up to Wordpress 5.2

= 1.0.4 =
* Tested up to Wordpress 4.9

= 1.0.3 =
* Fix Plugin URI
* Add preload scritp in the head

= 1.0.2 =
* Tested up to Wordpress 4.7

= 1.0.1 =
* Fix: move only scritps to footer and not styles.

= 1.0.0 =
* Initial release.