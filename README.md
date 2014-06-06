Overview 
========
This guide covers installation instructions and general information about Zuki's Atlassian Plugin.

Why?
====
Why do I need to use an add-on instead of downloading the app via the Apple App Store or Google Play?

* **Features.** This add-on allows you to intercept every event from your JIRA instance to unlock a very powerful feature: Push Notifications.
* **30-day trial period.** Using this add-on you can try out both iOS and Android apps for free.
* **Administration.** As a company you will pay Zuki's subscription the same way you pay for JIRA, through the Atlassian Marketplace.
* **Support.** Zuki's development team will tweak the app in order to get it working for your organization, at no additional cost.

Installation
============

Add-on installation
-------------------

1. Log-in to your JIRA instance as an admin.
2. Click the admin dropdown and choose the Atlassian Marketplace option.
3. Click *Find new add-ons* from the left-hand side of the page.
4. Find *Zuki for JIRA* via search.
5. Click *Try free* to begin a new trial or *Buy now* to purchase a license for Zuki for JIRA.
6. Enter your information and click *Generate license* when redirected to MyAtlassian.
7. Click *Apply license*.

Download Zuki
-------------

After installing the add-on you need to download Zuki for JIRA from the Apple App Store or Google Play. Choose the FREE version of Zuki on both marketplaces.

Here are the links:
Android version,
iPhone and iPad version.

Network permissions
-------------------
Zuki will try to access 2 servers:
- Push Notification Server.
- Crashlytics Server. 

**Push Notification Server**

This server is responsible for sending Apple Push Notifications. Currently we only support APNs.
The URL https://push.zukiapp.com has to be accessible from the JIRA server which has Zuki's plugin installed.  

**Crashlytics Server**

Crashlytics (http://crashlytics.com) is a broadly known and powerful crash reporting solution. Some components of this tool are hosted on Amazon, so at some point it is possible that Zuki will try to access Amazon's servers.

Login considerations
--------------------
You can log-in to Zuki using your **JIRA's username**. Zuki doesn’t support log-in with email or Google Authentication yet. 


How to use it
=============

Once you download Zuki and your JIRA’s administrator has installed the plugin, you are ready to go.

Login
-----

Simply open Zuki and complete the information to login:

![Login](screenshots/Login.png?raw=true)

URL: As shown in the screenshot, you have to enter JIRA’s URL, including the prefix HTTPS or HTTP depending on your  configuration. The JIRA connection port is also important. For example: https://intranet.moove-it.com:2990/jira/

Username: Your JIRA username.

Password: Your password.

Activity feed
---------------------------------

![Activity Feed](screenshots/ActivityFeed.png?raw=true)

It shows all the activity from the issues you are currently following (watching). 
By using this feed, you can get a quick overview of the issues you are watching.

If you are no longer interested, you can always unfollow issues by simply swiping right. 

If you want to reply to a comment, you can easily do it by swiping left and selecting the option.


Issues assigned to me
---------------------------------------

Contains all the issues assigned to you. 

![My issues](screenshots/MyIssues.png?raw=true)

You can also follow and unfollow tickets assigned to you by swiping right. If you are following an issue, a green indicator will appear in the upper-right corner.

![Follow from my issues](screenshots/FollowFromMyIssues.png?raw=true)

You can sort your issues by due date, priority or last activity. By default, the issues are sorted by priority and last activity.

![Sort](screenshots/Sort.png?raw=true)


All the issues
---------------------------------

![All Issues](screenshots/AllIssues.png?raw=true)

Contains every issue for every project you are involved with. These issues are sorted by last activity, so recently updated issues appear at the top of the list. 

Search tickets
-------------

The search box is located in the application side menu.

![Search](screenshots/Search.png?raw=true)

You can search a ticket by key or content. Results will include tickets matching the searched string in the description, summary or comments.

JIRA filters
------------

Zuki displays your favorite JIRA filters, along with the number of tickets for each of them. 

![Filters](screenshots/Filtes.png?raw=true)


Filter by project
-----------------

You can filter and unfilter by a specific project, each of the three tabs.

![Projects](screenshots/Projects.png?raw=true)

Actions over issues
------------------

![Options](screenshots/Options.png?raw=true)


Credits
=======

![Moove-IT](http://moove-it.com/assets/logos/mooveitLogo-f5be7bdde9998bbdfae39475d3f3d460.png?raw=true)

Zuki is a product of Moove-IT (www.moove-it.com)

Website: www.zukiapp.com

Support: support@zukiapp.com






 


