---
title: Wordpress
description: This is a post about the Wordress content management system
date: 2022-06-03
tags:
  - Tech
layout: layouts/post.njk
---

### Intro

[Getting Started](https://wordpress.org/support/category/getting-started/)



### WP-CLI
[How to WP-CLI](https://make.wordpress.org/cli/handbook/how-to/)

[Install WP-CLI](https://make.wordpress.org/cli/handbook/guides/installing/#recommended-installation)

[Install Wordpress (Needs MAMP installed and running for MySQL DB creation)](https://make.wordpress.org/cli/handbook/how-to-install/)

[Start a local test server (Also needs MAMP)](https://make.wordpress.org/cli/handbook/how-to-start-webserver/)

### Useful resources
[How to Install WordPress on Google Cloud (In 3 Steps)](https://themeisle.com/blog/install-wordpress-on-google-cloud/)

[WP-CLI Guide: Connect to WordPress via SSH Intro](https://blog.sucuri.net/2015/07/wp-cli-guide-connect-to-wordpress-via-ssh-intro.html)

[Installing WP-CLI with MAMP](https://tommcfarlin.com/installing-wp-cli-with-mamp/)

[Run WordPress on App Engine standard environment](https://cloud.google.com/community/tutorials/run-wordpress-on-appengine-standard)

### Common errors/slip-ups

https://wordpress.stackexchange.com/questions/290793/wp-cli-error-establishing-a-database-connection-in-localhost-mamp

WP CLI "Error establishing a database connection" in localhost (MAMP)

Error establishing a database connection. This either means that the username and password information in your `wp-config.php` file is incorrect or we can’t contact the database server at `localhost`. This could mean your host’s database server is down.

Go into your wp-config.php and change your DB_HOST to 127.0.0.1 instead of localhost.

https://stackoverflow.com/questions/47309091/with-wp-cli-wp-config-create-generates-error

### Useful resources/links

https://www.mamp.info/en/downloads/
https://medium.com/@tomlarge/wordpress-made-easy-with-wp-cli-9d52b298c5a6