# Getting started with Orbit

Welcome to Orbit! 

This guide will walk you through the process of creating and launching your Orbit workspace.



## Part 1: Setting up your spreadsheet

The first thing you'll need to do is install our Google Sheets Add-On, which is how Orbit communicates with your Google Sheet. 

Install the add-on at [this link](http://bit.ly/orbitaddon). We recommend you use **Google Chrome**, but Safari or Firefox should also work well.

Once you install the add-on, an empty spreadsheet will open in a new tab and you'll be prompted to allow Orbit certain permissions related to your Google Account. Please refer to our [Terms of Conditions](http://typora-app/TypeMark/avinalabs.com/legal) if you have questions relating how we use these permissions.

*If you get a warning about the app not being verified: click on Advanced option towards the bottom-left of the dialog and select Go to Orbit.*

When the app's installed, you should see the menu for Orbit appear in the Add-ons menu.

![img](file:///Users/shomil/Desktop/Screen%20Shot%202019-03-20%20at%206.01.00%20PM.png?lastModify=1553190892)



At this point, click on **"Reset to Template"** to import the Orbit template into this empty sheet. 

*While Orbit is in beta, you'll see a pop-up alert with a link to a Google Form. You'll need to fill this out to request early access. Make sure to include a link to the spreadsheet that you just created when you submit the Google Form! About 2-3 minutes after you submit the form, you should be able to proceed. Click on "Reset to Template" once again.*

If you see a "Welcome to Orbit" page, congratulations! You're ready to proceed. 



## Part 2: Configuring your workspace

At this point, you're ready to begin configuring your organization's workspace. We'll walk you through the different sheets – we strongly recommend you proceed in order!

As you proceed, look out for the light-gray blocks of text: these are examples that you can use for reference.

**A very important note – if you're ever pasting anything into the spreasheet, use Cmd+Shift+V on Mac or Ctrl+Shift+V on a PC. This will ensure that the spreadsheet retains its formatting, which is required for publishing your workspace.** 



#### General

First, start by entering general information about your workspace. 

|                   |                  |
| :---------------- | :--------------- |
| Organization Name | Berkeley SkyDeck |
| Mobile App Name   | SkyCentral       |
| Brand Color       | `#003262`        |

Next, add a few important links.

| Links             |                                           |
| :---------------- | :---------------------------------------- |
| Organization Icon | <https://bit.ly/2ugwgVj>                  |
| News Feed or Blog | <https://skydeck.berkeley.edu/news/>      |
| Social Media      | <https://twitter.com/skydeck_cal?lang=en> |

Make sure your organization icon is a direct link to an image; in other words, it should download immediately if you click on it. This is generally the format for images throughout.



#### Users

Orbit lets you customize your workspace to display different information to different categories of users. 

1. **User Type** – enter the category of users

2. **Login Type** – if you want to restrict access to your app to certain email addresses, you may do so by selecting Google Sign In and continue. To make a specific user type open to anyone, select *No Restriction* and skip to the next user type.

3. **Restriction Type** – you can either choose to restrict access to an approved list of users ("Restrict to List") or to users with emails in a particular domain ("Restrict to Domain").

   > If you choose "Restrict to List", use the Add-On menu to insert an "Approved User" sheet. On this sheet, you'll be able to paste a list of approved emails sorted by user category.

1. **Email Domain** – paste all approved email domains into this cell (comma-separated values)



## Part 3: Incorporating resources

### Choosing what goes where

As you're bringing together resources for your organization, think about splitting your resources into two categories:

1. Items used on a day-to-day basis

   > Examples: campus maps, announcements, Google Forms, directories, toolkits

2. Resources used on a less-frequent basis (but still important to include)

   > Examples: tech support, HR paperwork, website links, general team information, miscellaneous resources

These two categories define the configuration of resources in Orbit. There's the **home page**, which contains the stuff your users need day-to-day, and there's the searchable **resources page**, which acts as a pseudo-mini Google Drive folder categorizing a bunch of different resources.



|                         Home Screen                          |                       Resources Screen                       |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![img](file:///Users/shomil/Documents/GitHub/Avina%20Labs/Vision/Vision-Assets/Mockups/ucb_home_iphonexspacegrey_portrait.png?lastModify=1553190892) | ![img](file:///Users/shomil/Documents/GitHub/Avina%20Labs/Vision/Vision-Assets/Mockups/ucb_resources_iphonexspacegrey_portrait.png?lastModify=1553190892) |
|                                                              |                                                              |



### Actions & Action Types: An Overview

When you're choosing which features to incorporate, you have the following options to choose from. These are quite flexible and can be molded into pretty much any type of resource you'd like to include!

On the Home Screen and Resources Screen, you link specific rows in your app to specific actions. The action types that you may choose from are defined below.

A clarification on language:

**Action Types** are the type of action that you're linking to.

> Choose from the drop-down list: Directory, Map, Web, Text, or Toolkit

**Actions** are the content that you're linking to. 



| Action Type |                         Description                          |                          Screenshot                          | Requires  Tab? |
| :---------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------------: |
|  Directory  | A list of information. Useful for member lists, team lists, inventory lists, etc. Tapping on a list item leads to a **detail page**. | ![img](file:///Users/shomil/Documents/GitHub/Avina%20Labs/Vision/Vision-Assets/Mockups/lghs_clubs_iphonexspacegrey_portrait.png?lastModify=1553190892) |    **Yes**     |
|     Map     | A rich map-based interface for your users. Useful for **indoor** or **outdoor** maps. | ![img](file:///Users/shomil/Documents/GitHub/Avina%20Labs/Vision/Vision-Assets/Mockups/ucb_campusmap_iphonexspacegrey_portrait.png?lastModify=1553190892) |    **Yes**     |
|     Web     | A in-app interface for handling website links. **Can link to Google Forms for data-entry, website links, and pretty much anything else** | ![img](file:///Users/shomil/Downloads/mockup%20(10)/IMG_2719_iphonexspacegrey_portrait.png?lastModify=1553190892) |     **No**     |
|    Text     | A quick way of displaying paragraphs of **text** or specific **messages** to your organization. | ![img](file:///Users/shomil/Documents/GitHub/Avina%20Labs/Vision/Vision-Assets/Mockups/lghs_announcements.png?lastModify=1553190892) |     **No**     |
|   Toolkit   | A toolkit-style page to bring together important **phone numbers**, **forms**, and basically anything of **uility**. | ![img](file:///Users/shomil/Documents/GitHub/Avina%20Labs/Vision/Vision-Assets/Mockups/ucb_safety.png?lastModify=1553190892) |    **Yes**     |
|  Calendar   | All of your organization's calendars, centralized. Users can choose which calendars to show/hide at any given time. | ![img](file:///Users/shomil/Documents/GitHub/Avina%20Labs/Vision/Vision-Assets/Mockups/ucb_events.png?lastModify=1553190892) |    **Yes**     |



### Home Screen

OK – now that you know what options you have to choose from, you're ready to create your home screen! On this sheet, you should see four different sections, one for each user type that you've defined. It's OK if some of these are empty if you're using less than four user categories.

For each user category:

1. Enter a feature title.

   > Keep it short and sweet! See the screenshots above for examples.

2. Select an Action Type.

3. Select an icon. 

   > To see all available icons, go to [this page.](http://ionicons.com/)

4. Enter an Action.

   > If you choose **Web**, then enter the *website link* here.
   >
   > If you choose **Text**, then enter a *block of text* here.
   >
   > If you choose anything else, then you'll need to first insert a tab that contains information about that page using the drop-down menu (Orbit => Add a Feature). Then, enter the *name of the sheet* that was just created. Feel free to rename the sheet to whatever you'd like.

5. Enter a subtitle.



#### Today View

The Today View is an extension of the Home Screen. It's that little colored section at the top of the home screen. The **main** **shortcut** refers to the bottom line (*"Tap here for today's dining hall menu"*). The **right** **shortcut** refers to the right-side shortcut underneath the weather (*"Campus Map"*).

| The UC Berkeley workspace displays a quick link to the Dining Hall Menu and the Campus Map. | The SkyDeck Accelerator workspace displays a quick link to the latest podcast and the Campus Map. |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| ![img](file:///Users/shomil/Library/Application%20Support/typora-user-images/image-20190321101046049.png?lastModify=1553190892) | ![img](file:///Users/shomil/Library/Application%20Support/typora-user-images/image-20190321103922058.png?lastModify=1553190892) |



### Resources

This page is optional – but very useful for organizations that typically rely on a large amount of shared Google Doc folders, old websites, or paper handouts. It's accessible through the **sidebar of your workspace**.

Start by listing out a few big categories that you want to segment your resources into.

Then, proceed to fill out the lower section by following the same format you used for the Home Screen.



## Part 4: Publishing your workspace

Congratulations! You're now ready to publish your workspace. After looking over all of the required sheets (marked in red) to check for typos and/or missing information, go ahead and **select "Publish" from the drop-down menu**. The Upload sheet will automatically open, and the status cell shoudl cotnain a yellow "Validating" status.

If your workspace is validated, it will become instantly available for your users to access through the Orbit app for iOS (currently invite-only through TestFlight) and Android (coming soon).

If the cell turns red, you likely have a formatting mistake somwhere (i.e. missing a URL for a Web action, incomplete data, etc.). Go ahead and fix the issue and then re-publish. **If you can't figure out what's wrong or the error is unreadable, use the drop-down menu to send a "Debug Email."** We'll get back to you with a fix as soon as possible.
