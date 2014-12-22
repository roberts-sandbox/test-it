---
layout: post          #important: don't change this
title: "Administer Visual Studio Tags using TagAdmin Visual Studio extension"
date: 2014-12-22 00:25:00
author: Tarun
categories:
- blog                #important: leave this here
- TagAdmin
img:        #place image (850x450) with this name in /assets/img/blog/
thumb: thumb.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---
Manage Work Item tags from right with in Visual Studio using the TagAdmin extension. Watch this 2 minute video to get a headstart...
<!--more-->
Tagging as a feature has been a hit in the Team Foundation Server / Visual Studio Online family of tools.

Work Item Tags allow you to associate identifiers to work items to group search and filter work items easily. Tags can be added directly from the work item form or using the excel plug in. Adding tags is so easy that they start to grow in no time. While that's a good thing you may not want people to create multiple tags that refer to the same thing. For example, BackOffice and Administration may have been created by users to refer to the same idea. However, these are now 2 separate entities, you will not be able to bring back work items tagged to BackOffice if searching exclusively for work items tagged to Administration. It’s also very easy to end up with tags that are misspelled.

So, the problem as it stands out today is... How do you manage tags in projects and project collections? 

We are very excited to announce the release of our latest Visual Studio Extension "TagAdmin"... The extension uses the all new REST APIs for retrieving and updating the data in TFS/VSO. The extension makes use of Integrated authentication to ensure all communication between the client & server is through an authorized token flow. The latest version of the extension can be downloaded from the Visual Studio Extension Gallery here. The first version of the extension allows you to,

1. View Active tags 
2. Rename tag
3. Delete tags 
4. View work items linked to tags
5. Supports both VSO and TFS 
6. Uses Integrated Authentication

Watch this 2 minute video of what the extension allows you to do today... 

If you like our work, we would love for you to spread the word for us... 
"Manage your workitem tags right from within #VisualStudio using #TagAdmin #VisualStudioExtension http://a.com developed by @onlyutkarsh @arora_tarun" 

We are still hard at work, do you have any ideas on how we can improve the extension? We would love to hear from you... Please drop us a line or better leave your suggestion on our user voice website... 
