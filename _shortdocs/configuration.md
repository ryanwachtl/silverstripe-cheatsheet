---
title: Configuration
sort: 1
external: http://doc.silverstripe.org/en/developer_guides/configuration/
---

<h4>Configuration API</h4>

<pre class="prettyprint lang-php">
// Accessing
Config::inst()->get('MyClass', 'property');
// Updating
Config::inst()->update('MyClass', 'property', 'foo');
// Removing
Config::inst()->remove('MyClass', 'property');
</pre>