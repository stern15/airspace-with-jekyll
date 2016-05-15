---
layout: post
title: benefits of static website
date: 2016-04-23 12:33
author: semasuka stern
image: http://placehold.it/900×300
lead: "If there is a lesson to be learned, it is the futility of seeking fulfillment in outer space. we need to judge ourselfs by who we are, not by where we go."
category: jekyll
sutitle: create an ultra fast, secure blog that is easy to maintain and scale
---


**Flexibility**
CMSs normally constrain your options, because they’re tied to a database with specific fields. If you want to add a Twitter widget to some pages, you’ll normally require a plugin, a shortcode or some custom functionality.

In a static site, the widget can simply be inserted into a file directly or using a partial/snippet. There are few limits, because you’re unshackled by the those imposed by a CMS.

**Better Performance**
Most CMS applications offer built-in or plugin-powered cache systems to ensure pages are generated and reused when possible. This is effective, although the overhead of managing, validating and re-generating cached pages remains.

Static sites are pre-cached pages which never expire. Files can also be minified prior to deployment to guarantee the smallest load. A static site will always perform better than a CMS-powered version using a similar template.



**Fewer Server-side Dependencies**
A typical WordPress installation requires:

a suitable operating system such as Ubuntu or CentOS
a web server such as Apache or NGINX
PHP with associated extensions and web server configurations
MySQL
the WordPress application
any necessary plugins
the theme/template code.
These dependencies must be installed and managed. WordPress requires less effort than some other applications, but it’s still possible for a single update to any part to cause chaos.

A static site is lightweight, and can be hosted by any web server able to return HTML files. There is nothing else to install, manage or update.

**Improved Reliability**
A CMS is complex, with many moving parts and points of failure. Run a WordPress site for any length of time and you’ll almost certainly encounter the dreaded “Failed to establish a database connection” error. Unforeseen CMS problems can arise from sudden traffic surges, which crash the database or restrict active connections.

Serving a static site is less intensive — the server just has to return flat files. It’s still possible to crash a web server, but it’ll take considerably more concurrent requests.

**Superior Security**
There are several reasons why someone may want to attack your website. Traffic hijacking, rogue advertising, linking, authenticity spoofing and malware hosting all permit an unauthorized user to make monetary and/or kudos gains.

A CMS opens a number of attack vectors. The most obvious is the login screen: it’s only as secure as the weakest user password. Be aware that any page running server-side code also offers potential exploits — for example, firing spam emails via your contact form. It may not be obvious that someone has gained access; the worst culprits want to stay hidden.

A static site has little or no server-side functionality. You cannot access it via scripting or database security holes. Someone could still gain access via SSH or FTP, but they would struggle to do much damage other than defacing pages or uploading files. A quick git status or folder check can reveal break-ins. It’s then simple to change passwords, wipe the whole site and regenerate it again.

**Client Control Considerations**

You spend weeks building attractive CMS themes for the client to trash their site within minutes of your hand-over. Using a CMS is not necessarily easy, and it offers considerable power to content editors. You can lock down rights such as plugin installation, but it won’t prevent someone changing fonts, adding weird colors, using poor photography or corrupting the layout.

A static site can use Markdown files. That limits the user’s options; they make fewer mistakes and cannot adversely affect the pages. Some will miss the CMS content administration panels, but you can either:

use their existing CMS and cleanse data before generation, or
provide simpler workflows such as editing Dropbox files in StackEdit.

**Version Control and Testing**

Database data is volatile. A CMS permits users to add, delete or change content on a whim. Wiping the whole site is a few clicks away. You can back up databases but, even if that’s done regularly, you’re still likely to lose some data.
