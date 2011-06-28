=== Ustream Status ===
Contributors: katz515
Plugin Name: Ustream Status
Plugin URI: http://katzueno.com/wordpress/ustream-status/
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=R8S6WTYMY9SXG
Author: Katz Ueno
Author URI: http://katzueno.com/
Tags: livecasting, status, ustream, live cast
License: GPL2
Requires at least: 2.8.0
Tested up to: 3.1.3
Stable tag: 1.0.0

Display the online/offline status of a Ustream channel

== Description ==

"Ustream Status" is a widget plug-in to display the live/offline status of an Ustream channel, using the desired images.

Enter your desired Ustream channel, and it will fetch the online/offline status. Then it will display the online/offline status image of your choice.

Ustream is one of the major live casting service providers that anybody can start a live cast for free or even make money.

Check out the demo at (although you only see it when I'm live.)
http://katzueno.com/

I'm looking for your feedback! Please contact me via my website
or @katz515 on twitter.

Plug-in Support Page
http://katzueno.com/wordpress/ustream-status/

Also check out my other WordPress plugins
http://katzueno.com/wordpress/


== Installation ==

How to install and use it

1. Upload `ustream-status` folder to the `/wp-content/plugins/` directory or you can install from admin panel directly.
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Create Ustream account (if you haven't done so)
1. Upload two (2) images which indicates online and offline status
1. Go to `Theme` - `Widget` and set up your Ustream channel and enter the image URLs
1. Save

This plugin uses cache. You may have to wait for 120 seconds until you see the channel becomes live or offline. Please be patient!


== Frequently Asked Questions ==

= What do I need? =

In addition to WordPress site, you need to sign-up at Ustream.tv and start live casting.

= How do I sign up for Ustream? =

Click sgn-up icon from Ustream.tv

= I don't have any images for offline/online images =

You need to make your own images. I may make preset later if you ask me so.

= I'm live. But my status won't change. =

First, wait for 120 seconds. Ustream Status uses cache. It only check the live/offline status once every 120 seconds.

If you don't see the change os status after 120 seconds you become live, you may have misspelled your Ustream ID, your WordPress site may be having hard time reaching Ustream Server, or your IP may be blocked from Ustream Server.

= How can I check if Ustream server is working or not? =

In order to check if Ustream service itself is working or not, you could directly ping their server by going to

http://api.ustream.tv/php/channel/XXXX/getValueOf/status

Replace the last "XXXX" to your account ID (e.g., YokosoNews) when you're live. You should be able to see like `s:4:"live";`, in your browser.

If you're still having problem getting the status, you can think of the following situation

- You mistyped your Ustream channel ID
- You mistyped the wrong URL of images
- Ustream Server may be having some problem.
- Your WordPress server may be blocked from Ustream Server



== Screenshots ==

1. Setting menu at the widget

1. Ustream Status in action

== Changelog ==

= 1.0.0 = 

* The initial version. This version should work ok.

== Upgrade Notice ==

= 1.0.08 =

This is initial version.
