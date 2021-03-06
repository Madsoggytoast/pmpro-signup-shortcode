=== Paid Memberships Pro - Signup Shortcode ===
Contributors: strangerstudios
Tags: memberships, registration, pmpro, paid memberships pro, signup, sign up, shortcode, register
Requires at least: 3.5
Tested up to: 4.5.2
Stable tag: .1

Add a shortcode [pmpro_signup] that can be used to embed a sign up form for Paid Memberships Pro levels.

== Description ==

Use the [pmpro_signup] shortcode to embed a sign up form anywhere on your site. You can place it into sidebar widgets or use popover plugins like Optin Monster and Popup Maker to embed the form into a popover.

If the level is free, the account will be created and the member will be automatically redirected to the specified redirect page. If the level is not free, the user will be taken to the membership checkout page to enter billing information.
	
Note: This replaces similar functionality that used to be included in the PMPro Register Helper addon.

Shortcode attributes for `[pmpro_signup]` include:	

1. intro – (optional) Override the default 'Register for' text above the checkout form or hide the text completely. (default: true; 1. accepts: true, false, or your custom text)
1. level – (required) determines which level to use for the checkout form
1. login – (optional) Set this attribute to show a 'Log In' link below the submit button. (i.e. login='1')
1. redirect – (optional) Set the page to redirect to after form submission. (default: Membership Confirmation page. accepts: referrer, account, or your custom URL)
1. short – (optional) determines whether to show the Confirm E-mail and Confirm Password fields OR show E-mail Address field only. (default: false; Accepts: true, false, or emailonly)
1. submit_button – (optional) Change the 'Submit' button text on the checkout form. (default: 'Sign Up Now'; accepts: your custom text)
1. title – (optional) Show a heading (h2) with a default 'Level Name' above the checkout form or your custom text. (default: false; accepts: true or your custom text)

== Installation ==

1. Upload the `pmpro-signup-shortcode` directory to the `/wp-content/plugins/` directory of your site.
1. Activate the plugin through the 'Plugins' menu in WordPress.

Add a sign up form to a post/widget/page using a shortcode:

[pmpro_signup level="3" intro="0" redirect="referrer" short="emailonly" submit_button="Signup Now" title="Sign Up for Gold Membership"]

== Frequently Asked Questions ==

= I found a bug in the plugin. =

Please post it in the issues section of GitHub and we'll fix it as soon as we can. Thanks for helping. https://github.com/strangerstudios/pmpro-signup-shortcode/issues

== Changelog ==
= .1 =
* Initial version.
