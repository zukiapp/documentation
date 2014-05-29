Overview 
========
This guide covers installation instructions and general information about the Zuki's Atlassian Plugin.

Why?
====
Why do I need to use an addon instead of downloading the app using the Apple App Store or Google Play?

* **Functionality.** The addon allows you to intercept every event on your JIRA instance and unblock a great functionality: Push Notifications.
* **30-day-trial period.** Using the Atlassian Marketplace you can test both, iOS and Android applications for free.
* **Administration.** As a company you pay the service the same way as you pay your JIRA’s subscription.
* **Support.** The Zuki development team will adapt Zuki in order to get it working on your organization without extra costs.

Installation
============

Add-on installation
-------------------

1. Log into your JIRA instance as an admin.
2. Click the admin dropdown and choose Atlassian Marketplace.
3. Click Find new add-ons from the left-hand side of the page.
4. Locate Zuki for JIRA via search.
5. Click Try free to begin a new trial or Buy now to purchase a license for Zuki for JIRA.
6. Enter your information and click Generate license when redirected to MyAtlassian.
7. Click Apply license.

Download Zuki
-------------

After installing the Add-on you need to download Zuki for JIRA from the Apple App Store or the Google Play. Choose the FREE version of Zuki on both marketplaces.

Here are the links:
Android version.
iPhone and iPad version.

Network permissions
-------------------
Zuki will try to access 2 servers:
- Push Notification Server.
- Crashalytics Server. 

**Push Notification Server**

This server is responsable for sinding Apple Push Notifications.
The URL https://push.zukiapp.com has to be accesible from the JIRA server which will have the Zuki's plugin installed in.  

**Crashalytics Server**

Crashalytics (http://crashlytics.com) is a broadly known and powerful crash reporting solution. Some components of this framework are hosted by Amazon, so at some point Zuki will try to access Amazon servers.

Login considerations
--------------------
You can login Zuki using your username. Zuki doesn’t support login by email or Google Authentication. 


How to use it
=============

Once you download Zuki and  your JIRA’s administrator has  installed the plugin, you are ready to go.

Login
-----

Just open Zuki and complete the information to login:

SCREENSHOT

URL: As the screenshot shows, you have to enter the JIRA’s URL, including the prefix HTTPS or HTTP depending on your JIRA’s configuration. The JIRA’s connection port is also important. For example: https://intranet.moove-it.com:2990/jira/

Username: This field is about your JIRA’s username. Zuki doesn’t support your email or Google Authentication. 

Password: Your user password.

Activity feed (tab on the middle)
---------------------------------

SCREENSHOT

When you login the tab in the middle is the first one you see. That feed shows the activity of those issues you are following (watching). 
Using that tab you can easily know what happened with those issues you really take care about.

If you are not longer interested, you can unfollow issues just swiping to the right. 

if you want to reply a comment, you can easily take action by swiping to the left. The option modal pops out.

Issues assigned to me (tab on the left)
---------------------------------------

That tab contains all the issues assigned to you. 

SCREENSHOT

You can also follow and unfollow tickets assigned to you swiping right. if you follow an issue a green indicator turns on.

You can sort your issues by Due date, Priority or Last activity. By default issues are sorted by Priority, Last activity.

All the issues (tab on the right)
---------------------------------

SCREENSHOT

The tab on the right have all the issues of the projects you are involved. Those issues are sorted by Last activity, so updated issues are closer to the top of the list.

Search issues
-------------

The search is located on the top of the application menu.

SCREENSHOT

You can search an issue by key or you can search by content. The search looks at the content of comments, description and summary.

JIRA filters
------------

Zuki display the list of your favorite JIRA filters. The list also shows the issue counter for each filter.

SCREENSHOT

Filter by project
-----------------

Zuki also allows you to filter the three tabs by project. You can unfilter by clicking again on the project.

SCREENSHOT

Action over issues
------------------

SCREENSHOT

Actions:
- Comment
- Log work
- Workflow
- Assign
- Add attachment

Credits
=======

![Moove-IT](http://moove-it.com/assets/logos/mooveitLogo-f5be7bdde9998bbdfae39475d3f3d460.png?raw=true)

Zuki is a product of Moove-IT (www.moove-it.com)

Website: www.zukiapp.com

Support: support@zukiapp.com






 


