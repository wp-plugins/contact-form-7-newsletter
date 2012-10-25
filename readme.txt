=== Contact Form 7 - Constant Contact Module ===
Contributors: katzwebservices, katzwebdesign
Donate link:https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=zackkatz%40gmail%2ecom&item_name=Constant%20Form%207%20Constant%20Contact%20Module
Tags: Constant Contact, Contact Form 7, ContactForm7, Contact Form, Newsletter, Opt In, Email Marketing, form, signup, email newsletter form, newsletter form, newsletter signup, email marketing
Requires at least: 3.2
Tested up to: 3.4.2
Stable tag: trunk
License: GPLv2 or later

Easily integrate Constant Contact with the Contact Form 7 plugin.

== Description ==

> __This plugin requires a <a href="http://www.constantcontact.com/index.jsp" title="Sign up for a free Constant Contact trial" rel="nofollow">Constant Contact account</a>.__ <br />*Don't have an account?* Constant Contact offers a <a href="http://www.constantcontact.com/email-marketing/index.jsp" rel="nofollow">free 60 day trial</a>, so sign up and give this plugin a whirl!

Automatically add contact form submissions to Constant Contact lists that you choose! The plugin settings are configured on a per-form basis on the Contact Form 7 form configuration pages.

### Features
* Add contacts to multiple lists at once
* Sync form fields to Constant Contact fields, including your Custom Fields
* Add a newsletter opt-in checkbox to your form (see <a href="http://wordpress.org/extend/plugins/contact-form-7-newsletter/faq/">plugin FAQs</a> to learn how)

== Installation ==

1. Upload `contact-form-7-constantcontact to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go to Contact > Constant Contact menu in the WordPress sidebar
1. Enter your Constant Contact login information
1. Configure the Constant Contact section on the Contact Form 7 "Edit" form page

== Frequently Asked Questions ==

= Do I need a Constant Contact account? =
Yes, this plugin requires a <a href="http://www.constantcontact.com/features/signup.jsp" title="Sign up for Constant Contact" rel="nofollow">Constant Contact account</a>.

= Does this plugin allow for an opt-in checkbox =

Yes, by including a checkbox tag in the form such as:
`[checkbox add-email-list default:1 "Add Me To Your Mailing List"]`

Then add `[add-email-list]` to the "Opt-In Field" option in the Constant Contact section.

= Where is the settings page =

In the WordPress administration, navigate to Contact > Constant Contact in the WordPress sidebar. The URL should be `[yoursite.com]/wp-admin/admin.php?page=ctct_cf7`

== Screenshots ==

1. Constant Contact Module Configuration
2. On the Form Configuration Page

== Changelog ==

= 1.0.3 =
* Renamed Constant Contact API wrapper classes for better namespacing in order to fix <a href="http://wordpress.org/support/topic/plugin-contact-form-7-constant-contact-fatal-error-when-activating">fatal errors</a> when users already have a plugin with the same class names.
* Fixed issue with first-time form setup potentially breaking sites with PHP warnings, <a href="http://wordpress.org/support/topic/plugin-contact-form-7-constant-contact-plugin-doesnt-work-with-php-version-5310">as reported here</a>
* Improved documentation: there is now inline help when setting up form integration.
* Improved plugin translation support
* Fixed issue where forms were being sent to Constant Contact, even when integration checkbox was unchecked, <a href="http://wordpress.org/support/topic/plugin-contact-form-7-constant-contact-all-forms-are-connected-to-constant-contact">as reported here</a>

= 1.0.2 =
* Fixed issue with first-time form setup potentially breaking sites with PHP warnings, <a href="http://wordpress.org/support/topic/plugin-contact-form-7-constant-contact-plugin-doesnt-work-with-php-version-5310">as reported here</a>
* Improved documentation: there is now inline help when setting up form integration.
* Improved plugin translation support

= 1.0.1 =
* Improved documentation: there is now inline help when setting up form integration.
* Improved plugin translation support

= 1.00 =
* Liftoff!

== Upgrade Notice ==

= 1.0.3 =
* Renamed Constant Contact API wrapper classes for better namespacing in order to fix <a href="http://wordpress.org/support/topic/plugin-contact-form-7-constant-contact-fatal-error-when-activating">fatal errors</a> when users already have a plugin with the same class names.
* Fixed issue with first-time form setup potentially breaking sites with PHP warnings, <a href="http://wordpress.org/support/topic/plugin-contact-form-7-constant-contact-plugin-doesnt-work-with-php-version-5310">as reported here</a>
* Improved documentation: there is now inline help when setting up form integration.
* Improved plugin translation support
* Fixed issue where forms were being sent to Constant Contact, even when integration checkbox was unchecked, <a href="http://wordpress.org/support/topic/plugin-contact-form-7-constant-contact-all-forms-are-connected-to-constant-contact">as reported here</a>

= 1.0.2 =
* Fixed issue with first-time form setup potentially breaking sites with PHP warnings, <a href="http://wordpress.org/support/topic/plugin-contact-form-7-constant-contact-plugin-doesnt-work-with-php-version-5310">as reported here</a>

= 1.0.1 =
* Improved documentation: there is now inline help when setting up form integration.
* Improved plugin translation support

= 1.00 =
* Liftoff!