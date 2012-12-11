php-markdown
============

Dan Rosenstark's WP-Plugin modification for occasional PHP markdown. Sometimes you want Markdown, sometimes you don't. 

This is almost entirely based on PHP Markdown. PHP Markdown is a port to PHP of the Markdown perl script by John Gruber; PHP Markdown Extra adds new features to Markdown and is maintained in a separate "extra" branch.

Use this Wordpress plugin by activating it and then wrap your markdown in `<pre class="markdown">` and `</pre>` tags. This plugin also wraps your markdown in a div of class `markdown` for styling.

In addition, it handles [this rare bug in Mobile Safari](http://stackoverflow.com/questions/13811747/bizarre-result-on-safari-for-iphone-ol-li-a-or-ul-li-a).
