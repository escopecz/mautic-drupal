Mautic Drupal 7.x module
========================

This Drupal 7 module lets you add the Mautic tracking gif image to your Drupal website and embed Mautic forms in Drupal content.

### Installation

1. [Download](https://github.com/mautic/mautic-drupal/archive/7.x.zip) zip package.
2. In your Drupal; go to **Modules** / **Install new module**.
3. Upload the zip package you've downloaded in step 1).
4. Enable Mautic module.
5. Configure Mautic module - insert Mautic Base URL. Save Confuguration.
6. Go to **Structure** / **Blocks** / drag & drop Mautic block to Footer position.

### Mautic Tracking Image

Module will insert 1 px gif image loaded from your Mautic instance. You can check HTML source code (CTRL + U) of your Joomla website to make sure the plugin works. You should be able to find something like this:

`<img src="http://yourmautic.com/mtracking.gif" />`

There will be probably longer URL query string at the end of the tracking image URL. It is encoded additional data about the page (title, url, referrer, language).