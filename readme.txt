=== YOURLS: WordPress ===
Contributors: ozh, mojowill
Tags: ozh, twitter, yourls, tinyurl, isgd, is.gd, bitly, bit.ly, short url, url shortener, oauth, mojowill
Requires at least: 3.0
Stable tag: trunk

Use YOURLS (a free GPL URL shortener service) or another public service (tinyURL...) to create short URL of your posts.

== Description ==

[YOURLS](http://yourls.org/ "Your Own URL Shortener") is a free URL shortener service you can run on your webhost to have your own personal TinyURL.

This plugin is a bridge between [YOURLS](http://yourls.org/ "Your Own URL Shortener") and your blog: when you'll submit a new post or page, your blog will tap into YOURLS to generate a short URL for it.

Requires PHP 5.

Note that, for maximum fun, this plugin also supports a few other public URL shortener services (is.gd, tinyURL and bit.ly)

[Otto](http://ottopress.com/2011/modified-yourls-plugin/) took the original plugin and stripped out the Twitter crap, all I have done is put in a little fix so that you now connect to your remote YOURLS using the API signature instead of username and password!
	
== Screenshots ==
1. plugin admin interface
1. title helper: counts the number of characters to keep under the 140 limit
1. on the Write screen, you can (re)generate short URLs.

== Installation ==

Installation is, as usual :

1. Upload files to your `/wp-content/plugins/` directory (preserve sub-directory structure if applicable)
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Refer to the official plugin page for documentation, usage and tips