=== WP Auto Login ===

Contributors: renventura
Tags: Login
Tested up to: 5.0
Stable tag: 1.0.1
License: GPL 2.0+
License URI: http://www.opensource.org/licenses/gpl-license.php

Bypass login forms and automatically sign into any account.

== Description ==
This plugin was created for quick login when working locally. In the settings, you add the username and password for any account (i.e. "admin" and "admin"). By visiting <code>http://mysite.com/wp-admin/?wp_auto_login=true</code>, you will be automatically logged into the account owning the credentials you defined.

== Installation ==

= Install Automatically =

1. Search for WP Auto Login in the Add New Plugin section of the WordPress admin
2. Install & Activate

= Install Manually =

1. Download the zip file, unzip it and upload plugin folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

<em>How do I use this plugin?</em>

First, I highly discourage you from using this plugin on a live/production environment because it creates obvious security problems (anyone can sign into an admin account). Therefore, you should only use this plugin to skip the login process on local environments.

Once installed and activated, the plugin adds its settings to the General settings page. To use the plugin, simply choose an account to sign into and enter the username and password. For example, on my local sites, I use "admin" for the username and password. Therefore, I'd enter "admin" into these fields and save.

To automatically log in, visit your local site's /wp-admin/?wp_auto_login=true and the plugin will do the rest.

Again, DO NOT USE THIS PLUGIN ON LIVE WEBSITES.

== Screenshots ==

None

== Changelog ==

= 1.0.1 =
* Updated author info

= 1.0 =
* Initial version