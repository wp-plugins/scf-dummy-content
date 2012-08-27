=== Plugin Name ===
Contributors: stevecfischer
Tags: content, developer
Requires at least: 3.3
Tested up to: 3.3
Stable tag: 1.8.1

Quickly populate your site with dummy content.

== Description ==
I hate wasting time adding dummy content to a theme. 

SCF Dummy Content quickly populates a site with dummy titles, content and featured images. It can create posts, pages, custom post types and terms for registered taxonomies.

I appreciate your comments and any ideas for improvement! 

== Installation ==

1. Unzip and Upload all files in `scf-dummy.zip` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go the the Options page to customize the dummy content

== Frequently Asked Questions ==

= Can I upload my own images =

Yes you can. In the options page there is an image uploader just for that.

== Screenshots ==

1. Fresh WordPress install before SCF Dummy Content plugin is executed.
2. Fresh WordPress install after SCF Dummy Content plugin is executed.

== Changelog ==

= 1.0 =
* Intial Version.

= 1.5 =
* Added Screenshots

= 1.6 =
* Added option to edit the title for terms
* Created shortcode for creating terms. User can insert the term being created into its title.
* Did some minor CSS to make the wysiwyg smaller and table larger.
* Filtered out some of the built_in post types and taxonomies(attachement, navigation items)
* Add javascript confirm box before executing the create posts script.
* Default post titles are "post_type" + number of post.
* Default term titles are "taxonomy name" + number of term.
* Added screenshots for WP.org

= 1.7 =
* Added functions to delete all posts and terms created by plugin.  Thus deflating the site.
* Added link to Ipsum Lorem Generator

= 1.8 =
* Edited some content.

= 1.8.1 =
* Bug fix - user could only create posts and no other custom post types
