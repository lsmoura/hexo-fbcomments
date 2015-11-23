hexo-fbcomments
===============

A simple way to add facebook comments support to a theme's articles.

Usage
-----

Install the plugin, and setup the config properly. If there is no configuration, the plugin will do nothing.

The theme needs to call a ```<%- fbcommentshead() %>``` on header (before the body tag) and ```<%- fbcomments(post.permalink) %>``` on the place that you want the comments to appear.

Configuration
-------------

Put the following code inside your _config.yml. Change values as needed.

``` yml
# Enable facebook comments
fbcomments:
  enabled: true
  lang: en_US
  appId: 0
  numPosts: 20
```

Parameters

* **enabled** (optional) enable/disable your plugin in a pinch
* **lang** (optional) the language to serve the facebook comments (default: en_GB)
* **appId** (required) the AppID responsible for the comments
* **numPosts** (optional) number of posts. Default: 5.

More
----
More information about the facebook comments plugin on the [Official Documentation](https://developers.facebook.com/docs/plugins/comments)

Author
------
Created and mantained by Sergio Moura.

License
-------
**MIT**