=== Remove Social ID for WP ===
Contributors: nitin247
Donate link: https://nitin247.com/buy-me-a-coffee/
Tags: fbclid, redirect, 301 redirect, remove fbclid, remove fbclid for wordpress
Requires at least: 6.0
Tested up to: 6.6
Stable tag: 1.1
Version: 1.1
Requires PHP: 5.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Remove Facebook Social ID, Google Adwords ID for Wordpress, removes querystring fbclid,gclid and redirects the URL for your WordPress site.

== Description ==

Facebook, Google(adwords) is now adding a fbclid,gclid argument to all the shared URLs respectively. Each visitor/user now comes from Facebook with a unique URL, because of this cache and various other functionality breaks on Wordpress site. 

Specially redirect rules get broken and pages show 404 error sometimes.

This plugin scans the incoming url for <b>fbclid,gclid</b> and redirect to the url after removing the querystring.

== Installation ==

* Upload the directory '/remove-social-id/' to your WP plugins directory and activate from the Dashboard of the main blog.

== Frequently Asked Questions ==

None at this time

== Changelog ==

= 1.0 =
First version release
= 1.1 =
Added support for GCLID ( Google Adwords )
