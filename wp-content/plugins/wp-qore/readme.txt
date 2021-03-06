=== WP Qore ===
Contributors: phatjay
Tags: security, performance, qore
Requires at least: 3.3
Tested up to: 3.8.1
Stable tag: 4.8
License: GNU GPL 3.0
License URI: http://www.gnu.org/licenses/gpl.html

WordPress Security, Developer Tools Plugin.

== Description ==

<a href="http://wpqore.com/">WP Qore</a>, a plugin that provides additional security, performance functionality, developer tools that can be turned on or off at any time. A great plugin for WordPress developers.

Features:

* login security
* customize login page
* hide login page
* replace dashboard
* disable nag updates
* admin bar removal
* use jquery cdn
* shortcode in widget
* php in widgets
* import/export widgets
* remove wp version
* minify your html
* gzip compression
* cleanup wp meta
* new theme directory
* unique source code

== Installation ==

This will activate the WP Qore WordPress Plugin.

1. Upload `wp-qore` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Adjust options within 'WP Qore' admin menu

Once activated, please update your options via the WP Qore menu located within the left side of the wp-admin.

== Frequently Asked Questions ==

= How do you see this plugin differentiating itself from others like Better WP Security, Hide My Login, or W3TC?  =

I can't say this plugin compares with the others. It wasn't created to compete with others. Truthfully, this plugin was created for myself. The functionality the plugin provides I use often with my own and even client sites. So I basically created a lightweight plugin that would serve the purpose of a way to turn on and off certain functionality preferably security and performance related things.

= Do you have a Github repository, too? =

Yes. We currently have WP Qore on Github. You may find the project here: https://github.com/icryptic/wp-qore

== Screenshots ==



== Changelog ==

= 1.0.9 =
* Updated code to use prepare() with queries to protect them from sql injections.

= 1.0.8 =
* Visual fix. Added two line breaks on db audit panel.

= 1.0.7 =
* Disabled calling wp-load directly on line 4.

= 1.0.6 =
* Replaced deprecated function in functions.php, has_cap to manage_options.

= 1.0.5 =
* Fixed minor bug with import/export widgets

= 1.0.4 =
* Enabled import and exporting of widgets. 
* Fixed small bug in functions.php pertaining to if{shortcode}.

= 1.0.3 =
* Enabled php in widgets. 
* Updated project description.

= 1.0.2 =
* Deprecated self-hosted plugin updater in preparation for the WordPress.org repository.

= 1.0.1 =
* Fixed a bug in updater. This was pre-wp repo.

= 1.0 =
* Initial Release

== Upgrade Notice ==

= 1.0.9 =
* Upgrade to fix possible security vulnerbility.

= 1.0.8 =
* Fix to Database Optimization Audit panel.

= 1.0.7 =
* Upgrade to fix possible security vulnerbility.

= 1.0.6 =
* Upgrade to fix deprecated function in functions.php.

= 1.0.5 =
* Upgrade to fix minor bug with import/export widgets.

= 1.0.4 =
* Upgrade adds new functionality.

= 1.0.3 =
* Upgrade adds new functionality.

= 1.0.2 =
* Upgrade now for the latest version.

= 1.0.1 =
* Upgrade now to make sure you do not miss any future updates. This update fixes the WordPress updater to notify users upon new version upgrades.
