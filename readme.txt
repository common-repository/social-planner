=== Social Planner ===
Contributors: antonlukin
Donate link: https://wpset.org/about/
Tags: auto post, social networks, facebook, twitter, linkedin
Requires at least: 5.3
Tested up to: 6.5.5
Stable tag: 1.4.0
Requires PHP: 5.6
License: GPLv2 or later

Social Planner is a WordPress plugin for scheduling announcements of posts to your social networks accounts.

== Description ==
Social Planner is a WordPress plugin for scheduling announcements of posts to your social networks accounts. The following providers are currently supported: Facebook, Twitter, VK.com, OK.ru, Telegram, but you can easily add a new one yourself.
The whole process is completely automated. Just write a new post and either entire post or it’s nicely formatted announcement with backlink will be published to all your configured social networks. Plugin works with profiles, business pages, community pages, groups, etc.

= Configuration =
You need to have account with either Facebook, Twitter, VK.com, OK.ru, Telegram or all of them.
Please see detailed [installation instructions](https://wpset.org/social-planner/) with screenshots.

**Getting social networks Authentication tokens can be a little tricky. Please note that the plugin cannot affect this.**

= Features =
* Delayed announcement scheduling.
* Detailed descriptions of sending errors.
* Displaying previews of links in social networks.
* Gutenberg support.
* Direct links to the published posts from the "Edit" page.
* Simple markdown for Telegram posts.
* Image posts for all supported networks.
* Chars counter in the excerpt text area.

= Supported Networks =
* **Facebook** — Autopost to your business page or community page with ability to make **Image** posts.
* **Twitter** — Autopost to your account with ability to attach **Image** to tweets.
* **Telegram** — Autopost to the channel, group or chat using Telegram bot.
* **VK.com** — Autopost to your profile or group page with ability to make **Image** posts.
* **OK.ru** — Autopost to your groups with ability to make **Image** posts.
* **Linkedin.com** — Autopost to your profile or group with ability to attach image.

== Get support ==
First of all read the [Frequently asked Questions](https://wpset.org/social-planner/#faq) on the plugin documentation page.

If you find a bug or want to add new feature to this plugin, create new [issue](https://github.com/antonlukin/social-planner/issues) on Github or send a [pull reguest](https://github.com/antonlukin/social-planner/pulls).

== Screenshots ==
1. Add new post metabox
2. Scheduled and sent posts
3. Scheduled posts on dashboard widget
4. Settings Page

== Changelog ==

= 1.4.0 =
* Adding new provider for make.com.

= 1.3.2 =
* Bump 'Tested up' version and update readme

= 1.3.0 =
* Adding new provider for Linkedin.
* Adding `url` parameter to `social_planner_filter_request_body` filter for each network class

= 1.2.0 =
* Adding new provider for Twitter API v2.
* Removing local language files. Use https://translate.wordpress.org/projects/wp-plugins/social-planner/ interface

= 1.1.12 =
* Adding `social_planner_before_request` and `social_planner_filter_request_body` filters for each network class

= 1.1.11 =
* Fixing `subscribeOnSaving` error on Post editor while using Classic Editor

= 1.1.10 =
* Replacing invalid `social_poster_prepare_message` filter with `social_planner_prepare_message`

= 1.1.9 =
* Replacing official plugin site url

= 1.1.8 =
* Update readme and add WordPress catalog assets

= 1.1.7 =
* Replacing technical support links to a new website

= 1.1.6 =
* Bumb version to fix error with plugin update

= 1.1.5 =
* Update node modules and rebuild assets

= 1.1.4 =
* Add OK.ru provider

= 1.1.3 =
* Fix language text domain and replace screenshots

= 1.1.2 =
* Update plugin docs

= 1.1.1 =
* Change the minimum version of php to 5.6

= 1.1 =
* Initial version for WordPress Plugin Directory.
