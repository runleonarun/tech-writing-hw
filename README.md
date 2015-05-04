# What To Do

Below, you'll find the beginning of an article on setting up MediaWiki with the lighttpd web server on Ubuntu 14.04.  The introduction, prerequisites, and some section headers are included to get you started.  Edit these if you need to, but use them as a guideline for what your tutorial's scope should be.

An outdated version of MediaWiki is available through Ubuntu's repository, but you should tell users how to set up the latest stable version instead.

If you wish to expand the scope of the article, consider adding information about one of these:

* Securing your wiki with SSL
* Storing your wiki data in a remote database
* Creating rewrites to configure pretty URLs

Good luck!

----------------------

### Introduction

MediaWiki is a popular open source wiki platform that can be used for public or internal collaborative content publishing.  MediaWiki is used for many of the most popular wikis on the internet including Wikipedia, the site that the project was originally designed to serve.

In this guide, we will be setting up the latest version of MediaWiki on an Ubuntu 14.04 server.  We will use the `lighttpd` web server to make the actual content available, `php-fpm` to handle dynamic processing, and `mysql` to store our wiki's data.

### Prerequisites

To complete this guide, you should have access to a clean Ubuntu 14.04 server instance.  On this system, you should have a non-root user configured with `sudo` privileges for administrative tasks.  You can learn how to set this up by following our [Ubuntu 14.04 initial server setup guide](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-14-04).

When you are ready to continue, log into your server with your `sudo` user and get started below.

## Install the Server Components

## Configure MySQL and Create Credentials for MediaWiki

## Configure PHP-FPM and Lighttpd

## Install MediaWiki

## Conclusion



