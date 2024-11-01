=== Transform Meta Boxes ===
Contributors:      keith_wp
Author Link:       https://drakard.com/
Requires at least: 4.5 or higher
Tested up to:      6.5
Stable tag:        0.1.6
License:           GPLv3 or later
License URI:       https://www.gnu.org/licenses/gpl-3.0.html
Tags:              transform meta boxes, change taxonomy style, taxonomy style, meta box, meta boxes, change meta boxes, alter meta box, metaboxes


Alter any taxonomy's meta box appearance (**in the Classic Editor**) to single or multiple select dropdowns, or toggle button style checkboxes.

== Description ==

Change the appearance of a taxonomy's meta box input in the Edit screen to something other than the Category checkboxes or Tag free text entry, allowing you to have your users easily pick from a predefined set of terms.


== Installation ==

1. Upload the plugin files to the **/wp-content/plugins/transform-meta-boxes/** directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress
1. Use the Settings -> Transform Meta Boxes screen to configure the plugin, picking which taxonomies you want to transform and how.


== Frequently Asked Questions ==

= How do I add more terms now? =

These meta box alternatives remove the ability to freely enter new terms on the same Edit screen, meaning you need to add terms on the relevant taxonomy page first.

This is by design, so that it is harder to accidentally end up tagging your posts with typos or little used terms.


== Screenshots ==

1. The normal Post Categories before transformation, and after; top right as a single select dropdown and bottom right as a multiple choice one.
2. Term hierarchies are respected by the select dropdowns.
3. Turn your Tags into fancy buttons.
4. The Settings screen will let you alter any taxonomy which has been set to show in the UI.


== Changelog ==

= 0.1.6 =
* Tested against 6.4 and 6.5
* Bugfix: don't show non-public taxonomies like wp_pattern_category

= 0.1.5 =
* Tested against 6.3.2
* Bugfix: later versions of PHP didn't like when first activating the plugin

= 0.1.4 =
* Bugfix: changed deprecated way of calling settings page

= 0.1.3 =
* Tested against 5.2.1
* Will not work with Gutenberg until https://github.com/WordPress/gutenberg/issues/13816 is sorted

= 0.1.2 =
* Tested against 4.6.2
* Bugfix: Check for deactivated taxonomies
* Bugfix: Doesn't use the deprecrated get_terms() call now

= 0.1.1 =
* Tested against 4.6.1

= 0.1 =
* Initial release.


== Upgrade Notice ==


