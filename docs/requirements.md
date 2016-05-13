---
layout: docs
title: Requirements | Pattern Lab
heading: Requirements
languages: 
- language: php
- language: node
---

<!--- start php -->

<div class="tab-panel" id="php">
<h2 class="language-title">php</h2>

{% capture m %}

The requirements for the PHP version of Pattern Lab vary depending on what features you want to use.

## Minimum Requirements for Building Pattern Lab

It's expected that you'll use the PHP version of Pattern Lab locally on your computer to develop your atoms, molecules, organisms, templates and pages. To use the basic features of Pattern Lab, you must have **PHP 5.3+** installed. If you're using Mac OS X you shouldn't have to install anything and Pattern Lab should work "out of the box." If you're on Windows you can [download PHP from PHP.net](http://windows.php.net/download/#php-5.5).

You should _not_ need to set-up Apache or another web server to use Pattern Lab unless you want to use the [Page Follow feature](http://pattern-lab.info/docs/advanced-page-follow.html) for multi-device testing.

<small>**Note:** While the site will work in Safari 6+ the back button is broken in the "Apache-less" version of Pattern Lab.</small>

## Minimum Requirements for Hosting Pattern Lab

Once you want to show off your edition of Pattern Lab to a client you might want to put it on your web host. There are **no** requirements for hosting your Pattern Lab site. The Pattern Lab site consists of HTML, CSS, and JavaScript. Simply upload the `public/` directory to your host and you should be good to go.

{% endcapture %}
{{ m | markdownify }}

</div>

<!--- end php -->


<!--- start node-->

<div class="tab-panel" id="node">
<h2 class="language-title">node</h2>

{% capture m %}


The requirements for the Node version of Pattern Lab vary depending on what features you want to use, but are centrally managed using the `package.json` file.

## Minimum Requirements for Building Pattern Lab

It's expected that you'll use the Node version of Pattern Lab locally on your computer to develop your atoms, molecules, organisms, templates and pages. To use the basic features of Pattern Lab, most people will opt to use grunt with Node. This comes with any download you may pull down from [Github](https://github.com/pattern-lab/patternlab-node) or [npm](https://www.npmjs.com/package/patternlab-node).

A templating engine called [Mustache](https://github.com/janl/mustache.js/) ships with Pattern Lab to construct patterns. 

You should _not_ need to set-up Apache, IIS or another web server to use Pattern Lab. 

## Minimum Requirements for Hosting Pattern Lab

Once you want to show off your edition of Pattern Lab to a client you might want to put it on your web host. There are **no** requirements for hosting your Pattern Lab site. The Pattern Lab site consists of HTML, CSS, and JavaScript. Simply upload the `public/` directory to your host and you should be good to go.

{% endcapture %}
{{ m | markdownify }}

</div>
<!--- end node -->
