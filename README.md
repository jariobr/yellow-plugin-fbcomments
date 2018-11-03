FbComments plugin 0.7.4
===================
Add FbComments plugin comments to blog. [See demo](https://yellow.jar.io/).

<p align="center"><img src="fbcomments-screenshot.png?raw=true" alt="FbComments Screenshot"></p>

## How to install plugin

1. [Download and install Datenstrom Yellow](https://github.com/datenstrom/yellow/).
2. [Download and install blog plugin](https://github.com/datenstrom/yellow-plugins/tree/master/blog).
3. [Download plugin](https://github.com/datenstrom/yellow-plugins/raw/master/zip/fbcomments.zip). If you are using Safari, right click and select 'Download file as'.
4. Copy `fbcomments.zip` into your `system/plugins` folder.

To uninstall delete the [plugin files](update.ini).

## How to show comments

Create and ative the App Facebook in https://developers.facebook.com/apps/

FacebookId: 2000000000000000	

Facebook Comments is a comment mananger service freely for websites. To use the plugin open file `system/config/text.ini` and change `FacebookId: 2000000000000000`. You can find the name of your website in the FbComments dashboard. Comments are shown on blog pages. To show comments on other pages add a `[fbcomments]` shortcut to a page.


This plugin uses an online service, use the [comments plugin](https://github.com/wunderfeyd/yellow-comments) as an alternative.

## Developer

Datenstrom. [Get support](https://developers.datenstrom.se/help/support).   
https:github.com/jariobr
