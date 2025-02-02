=== AdSense Now! Redux ===
Contributors: manojtd, birkoffsjunk
Donate link: http://www.Thulasidas.com/buy
Tags: adsense, ad, ads, advertising, google, google search, widget
Requires at least: 2.5
Tested up to: 2.8.4
Stable tag: 1.8

AdSense Now! gets you started with Google AdSense. No mess, no fuss.

== Description ==

*AdSense Now! Redux* Same as *AdSense Now!* but with Ad Space sharing code removed.

*AdSense Now!* is the simplest possible way to generate revenue from your blog using Google AdSense. Aiming at simplicity, *AdSense Now!* does only one thing: it puts your AdSense code in up to three spots in your posts and pages (both existing ones and those yet to be written).

= Features =

1. Enforces the Google policy of not more than three ad blocks per page.
1. Simplest possible configuration interface -- nothing more than cutting and pasting AdSense code.
1. Option to suppress ads on all pages (as opposed to posts), or on the front/home page., category/tag/archive listings.
1. Control over the positioning and display of AdSense blocks in each post or page.
1. Internationalized with multiple language support.

PS: You'll need a [Google AdSense Account](http://adsense.google.com/).

= What's New in 1.80 =


If you think *AdSense Now!* is too lean and mean for your taste, try the full-fledged, feature rich plugin [Easy AdSenser](http://wordpress.org/extend/plugins/easy-adsenser/ "The complete solution for all things AdSense related").

If you like *AdSense Now!*, you may want to check out my other plugins: [Theme Tweaker](http://wordpress.org/extend/plugins/theme-tweaker/ "To tweak the colors in your theme with no CSS/PHP editing") and [Easy LaTeX](http://wordpress.org/extend/plugins/easy-latex/ "To display mathematical equations in your blog using LaTeX").

== Screenshots ==

1. How to set the options for *AdSense Now!*

== Installation ==

1. Upload the *AdSense Now!* plugin (the whole adsense-now folder) to the '/wp-content/plugins/' directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Go to the Setup -> AdSense Now! and enter your AdSense code and options.

== Frequently Asked Questions ==

= How can I control the appearance of the adsense blocks using CSS? =

All `<div>`s that *AdSense Now!* creates have the class attribute `adsense`. Furthermore, they have attributes like `adsense-leadin`, `adsense-midtext` and `adsense-leadout` depending on the type. You can set the style for these classes in your theme `style.css` to control their appearance.

= Ad Space sharing? in Redux =

Removed
[manojtd's Forum post](http://wordpress.org/support/topic/289189?replies=16)

= Why another AdSense plugin? =

The other plugin I have published, [Easy AdSenser](http://wordpress.org/extend/plugins/easy-adsenser/ "The complete solution for all things AdSense related"), does everything that *AdSense Now!* does and more. But in doing so, Easy AdSenser has become an All-in-One AdSense plugin, and not "Easy" any more. I wanted to go back to the basics and provide a simple plugin to get our fellow bloggers started on AdSense.

= I like its simplicity, but *AdSense Now!* doesn't have all the features I need. Can you add *this* and *that* feature? =

If you think *AdSense Now!* is too lean and mean for your taste, try my full-fledged, feature-rich plugin [Easy AdSenser](http://wordpress.org/extend/plugins/easy-adsenser/ "The complete solution for all things AdSense related"). I plan to keep *AdSense Now!* simple.

= I just activated the plugin. How come I don't see any ads in my blog? =

Note that you have to generate your adsense code from Google, and paste the *entire* code in the text box, replacing the existing text. Changing the publisher id alone is not good enough.

If you just created the new Google AdSense code, it may not be active yet. Google takes about ten minutes or so before serving ads. Please try again later.

= Can I control how the ad blocks are formatted in each page? =

Yes! Now, in V1.1+, you more options [through **custom fields**] to control ad blocks in individual posts/pages. Add custom fields with keys like **adsense-top, adsense-middle, adsense-bottom, adsense-widget, adsense-search** and with values like **left, right, center** or **no** to have control how the ad blocks show up in each post or page. The value "**no**" suppresses all AdSense ad blocks in the post or page.

= How do I report a bug or ask a question? =

Please report any problems, and share your thoughts and comments [at the plugin forum at WordPress](http://wordpress.org/tags/adsense-now "Post comments/suggestions/bugs on the WordPress.org forum. [Requires login/registration]") Or send an [email to the plugin author](http://manoj.thulasidas.com/mail.shtml "Email the author").

== Change Log ==

* V1.80: Releasing new Ukrainian and Polish, and updated Italian translations. [Sept 24, 2009]
* V1.77: Releasing new Arabic, and updated German, French and Indonesian translations. [August 22, 2009]
* V1.75: Compressing the defaults file. No functional improvements. [August 10, 2009]
* V1.74: A few more translations. (English users do not need to update.) [August 5, 2009]
* V1.64: Releasing `pt_PT` translation. [July 22, 2009]
* V1.63: New translation in Russian (`ru_RU`). Updated translations: Portuguese (`pt_BR`), Simplified Chinese (`zh_CN`). [July 18, 2009]
* V1.62: Attempts to fix automatic update and install issues. Improved documentation highlighting ad space sharing. Not an essential update, but any feedback will be appreciated. [July 16, 2009]
* V1.61: Changes to streamline internationalization. (English users don't need to update.) [July 14, 2009]
* V1.58: Admin page enhancements. Simplified Chinese translation. [July 2, 2009]
* V1.57: Removing min-max enforcing on ad space sharing. [June 30, 2009]
* V1.56: Fixing a typo in `is_category()`. [June 26, 2009]
* V1.55: Fixing the issue with submit buttons in IE8. [June 23, 2009]
* V1.54: Providing `htmlspecialchars_decode()` for compatibility with older versions of PHP. [June 23, 2009]
* V1.53: The `<div>` containing the adsense code has class names set so that they can be controlled from the theme CSS. The shared ad-slots are of the same size and show only text ads now. [June 23, 2009]
* V1.52: German translation. [June 20,2009]
* V.151: Compatibility with WP2.8+. [June 13, 2009]
* V1.50: Interface streamlining and improvements, minor bug fixes and configurable ad space sharing to support the plugin development. [June 12, 2009]
* V1.37: Option to suppress ad blocks in front/home/category/tag/archive pages. [June 6, 2009]
* V1.35: Belarusian translation. [May 4, 2009]
* V1.34: Turkish translation. [May 4, 2009]
* V1.33: Added some HTML comments in the page with version number and ad block sequence number for easy trouble shooting. [May 1, 2009]
* V1.32: More fixes to finally make the admin page totally "Valid XHTML 1.0 Transitional." Also releasing translation in Bahasa Indonesia.  [April 17, 2009]
* V1.31: Minor bug fix (related to the number of ad blocks on a page). [April 13, 2009]
* V1.30: Major overhaul of the interface. New clean look with javascript tooltips hiding details. New options to clean up the database entries and uninstall the plugin. [April 12, 2009]
* V1.21: An option to show ads only in blog posts (and not on pages). [April 9, 2009]
* V1.20: Internationalization, riding on the translations of Easy AdSenser. [April 4, 2009]
* V1.11: Bug fix: the plugin wasn't gracefully handling posts with no custom fields. [March 10. 2009]
* V1.10: Adding more control over displaying AdSense blocks in individual post. [March 8. 2009]
* V1.01: A serious bug fix. [March 6, 2009]
* V1.00: Initial release. [March 1, 2009]
