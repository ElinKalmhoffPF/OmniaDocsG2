Using Omnia Feed
===================

With Omnia Feed users can stay connected to the organization's Omnia Intranet wherever they are. 

Omnia Feed can be set up in many different ways to make it possible for users to read information from their organization's intranet, on their mobile device. A good example is News, but it can be any page(s) really, and anything that can be accessed by a link. 

Here's an example:

.. image:: omnia-feed-test-new.png

Any number of tabs can be set up for access to different resources. A tab can be set up for:

+ A Rollup (similar to a Page Rollup) to list news or other pages.
+ An Embedded link, which can be used to show the home page of an Omnia intranet, or to show some specific Omnia functionality - for example My Links or My Tasks.
+ An External link, which for example can be used as a shortcut to other applications (time report, HR system, etc).

Settings are found in Omnia Admin. There are settings for the tenant, mainly used by AM and the Omnia Feed Team to set up the tenant, and then settings for each Business Profile, where for example the tabs are set up. See this page for more information: :doc:`Omnia Feed - Business Profile Settings </admin-settings/business-group-settings/omnia-feed/index>`

The Omnia Feed App
*******************
The Omnia Feed app can be downloaded from the usual sources, for example App Store for iPhone.  

Regardless of how Omnia Feed is set up, using settings, a user can log out and select another Business Profile, if available.

The settings are available here:

.. image:: omnia-feed-settings-menu.png

Available settings are the following:

.. image:: omnia-feed-settings-available-new.png

Logging out is simply done by selecting "Sign out".

To select another Business Profile (if available), select the Business Profile and choose another one on this page:

.. image:: omnia-feed-settings-bp-new.png

Also note that the App Version is displayed here:

.. image:: omnia-feed-settings-version.png

Microsoft Authenticator or similar
---------------------------------------------
If your organization is using Microsoft Authenticator, a Company Portal, or similar, Omnia Feed will request permission to access the contacts list. This is required for the Omnia app to work with Microsoft Authenticator and similar solutions.

Important note about logged in status
--------------------------------------
If the user chooses to log out, the user will no longer receive push notificatons until logged in again.

If the user is being logged out automically due to an organization policy or similar, the user still receives push notifications for three weeks. After that, the user must log in to continue receiving push notifications.

Omnia Feed implementation example
*************************************
In this example:

.. image:: omnia-feed-tabs.png

My Feed and Product News are two different Page Rollups.

When reading news, users can see likes and comments for each News Article. 

.. image:: omnia-feed-likes-new.png

A user can like a News Article by selecting the hearth. To add a comment, the user scrolls down to the end of the article.

.. image:: omnia-feed-add-comment-new.png

In this implementation example, there's also a link to the start page of the Omnia Intranet. It may need an additional login:

.. image:: omnia-feed-intranet-new2.png

