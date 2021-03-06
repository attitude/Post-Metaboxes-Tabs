=== Post Metaboxes Tabs ===
Contributors: attitude_sk(http://www.attitude.sk)
Donate link: http://bit.ly/kl8KBw
Tags: metaboxes, tabs, post, page, administration, ui, clean, interface
Requires at least: 2.5
Tested up to: 3.2
Stable tag: 0.1

Groups mataboxes when editing post/page in administration backend to tabs according to metabox name pattern `Tab/Metabox`.

== Description ==

When you have a lot of metaboxes in the post/page edit screen, you end up scrolling which is confusing. Metaboxes
represent a group of fields like Address, or Ingredients, etc. Imagine you are creating a deep CV for a person. 
Suddently you have `Addresses`, `Contacts`, `Profile`, `Education`, `Skills`, `Languages`, etc. But as you can see
`Addresses`, `Contacts`, `Profile` can be categorized as `Personal Data.

This plugin lets you group metaboxes by anything, just name each metabox as `Tab / Box name`. So the
`Addresses` metabox should be named as `Personal Data / Addresses` and it will be grouped with `Personal Data / Contact`
under `Personal Data` tab.

Notes:

*	Both `Tab / Box name` and `Tab/Box name` or `Tab/ Box name` work
*	Built-in metaboxes are ignored (they usually sit in the sidebar and are needed all the time)
*   Although tested on 3.2, it should work since 2.5
*	Javascript enabled is required

== Installation ==

Installing plugin.

1. Upload plugin folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the `Plugins` menu in WordPress
1. Rename metaboxes or give them new names. That`s it

== Frequently Asked Questions ==

= How can I set order of tabs? =

Order of tabs depends on how you reorder the metaboxes in post/page edit screen.

= How can I set order to metaboxes when they are now hidden? =

Click the `Screen Options` in the upper right corner, turn every box on. As they appear, reorder them and reload
the page.

== Screenshots ==

1. Edit post/page screen in Wordpress admin with metaboxes using Magic Fields
2. Activated Post Metaboxes Tabs plugin generates tabs next to the title

== Changelog ==

= 0.1 =
* Initial release