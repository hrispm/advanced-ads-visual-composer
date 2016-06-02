=== Visual Composer Ads ===
Contributors: webzunft
Tags: ads, visual composer, frontend editor
Requires at least: 4.5
Tested up to: 4.5.2
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Manage ads in your Visual Composer interface.

== Description ==

This plugin combines the Visual Composer and [Advanced Ads](https://wordpress.org/plugins/advanced-ads/) plugin.

**Ad Management Features**

Advanced Ads is a powerful, but easy to use ad management plugin. Among the [many features](https://wpadvancedads.com/features/), you can:

* manage various kinds of ads like AdSense, DFP, Amazon, and any other custom code
* show ads for mobile/desktop users only
* automatically inject ads into content, after specific paragraphs
* use Pro visitor conditions like browser width, geo location, browser language and many more

**Instructions**

After activating this plugin, as well as Visual Composer and Advanced Ads, you should find three new Visual Composer elements in the editor:

* Advanced Ads – Ad
* Advanced Ads – Group
* Advanced Ads – Placement

Each of them corresponds to the according element in Advanced Ads. You only need to enter the ids/slug of that element to show it in Visual Composer.

**Where to find the IDs?**

Ads: Open the ad edit screen and stop the Wizard, if active. You should now see the Ad Id below the ad title.
Groups: The Group ID is listed in the Details column of the ad group list.
Placement: Create a _Manual_ placement. Open the list of placements and click on _show usage_ below the placement’s name. Extract the ID from the id attribute in the shortcode field

== Changelog ==

= 1.0 =

* first version