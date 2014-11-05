=== GooVain ===
Contributors: Aaron DeMent
Tags: links, twitter, short, url, socialmedia, permalinks, redirect, shorturl, goo.gl
Requires at least: 3.0
Tested up to: 4.0
Stable tag: 1.0

Uses Google's URL shortener (Goo.gl) to create short links for your WordPress posts, track analytics and allows for Vainity URL.

== Description ==

This plugin creates goo.gl short URLs for your posts, which then could be changed to the desired vanity url and retrieved using the "Get Shortlink" button in your admin UI or the `wp_get_shortlink()` WordPress function. This also changes the link rel='shortlink’ in the document head and ads a column in the post list showing the short url as well.

This plugin does all this without storing any values in the database. Instead it writes the shorturl to a text file and retrieves from said text file.

Note: Need to have a Short Url domain (your.com). The short url domain does not have to be pointed at the site or stored on the site, it just needs to be a valid domain.


== Installation ==

1. Upload archive contents to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Add you short url in Settings-> GooVain Settings 
1. You're done!

== Screenshots ==

1. Shortened URLs
2. Posts List and Analytics

== Change log ==
= 1.1 =
* added options page to change short url without editing code.
* added text file to store data instead of storing in the database.

= 1.0 =
* Hurray
