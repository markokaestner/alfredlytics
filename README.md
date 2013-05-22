Alfredlytics - Google Analytics Alfred 2 Workflow
=================================================

Features
--------

This workflow shows Google Analytics metrics and dimensions directly in Alfred 2:

* Visitors / Pageviews of the last 7 days
* Top Pages of the last 30 days
* Top Referrers of the last 30 days
* Top Searches of the last 30 days

![](https://dl.dropboxusercontent.com/u/5453663/alfredlytics.png)

Installation
------------

[Download](http://bit.ly/14vO5eS) and import into Alfred 2.

Usage
-----

### Keywords

Before you can use the workflow you have to configure your Google Analytics account. This will use Google OAuth2, so you will not have to save your Google credentials with the workflow.

#### Setup

* **`.gaauth [Google Auth Code]`** - Authorize workflow to access your Google Analytics data

First call the keyword without an argument. This will redirect you to Google's authorization website.

![](https://dl.dropboxusercontent.com/u/5453663/gaauth1.png)

![](https://dl.dropboxusercontent.com/u/5453663/gaauth2.png)

Copy the auth code and call the keyword a second time with the auth code as argument.

![](https://dl.dropboxusercontent.com/u/5453663/gaauth3.png)

![](https://dl.dropboxusercontent.com/u/5453663/gaauth4.png)

* **`.gaprofile`** - Choose your default profile

After you have authorized the workflow you have to choose your default profile.

![](https://dl.dropboxusercontent.com/u/5453663/gaprofile.png)

#### Show Google Analytics data

* **`.ga`** - Display GA Metrics

Currently you can view these metrics/dimensions:

* Visitors / Pageviews of the last 7 days
* Top Pages of the last 30 days
* Top Referrers of the last 30 days
* Top Searches of the last 30 days

Credits
-------

Thanks to [Jeffrey B. Murphy](http://www.jbmurphy.com/2013/01/11/2237/) and [Mario Alemi](http://www.visualab.org/index.php/using-google-rest-api-for-analytics) for their excellent articles on Google OAuth2 authentication on the shell. Also thanks to [Dominic Tarr](https://github.com/dominictarr/JSON.sh) for his great shell JSON parser.

Some of the icons are part of the "Web Design" icon pack created by [Liam McKay](http://wefunction.com/).
