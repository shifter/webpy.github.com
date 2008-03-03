---
layout: default
title: Web.py Cookbook
---

# Web.py Cookbook

Cookbook style documentation for web.py 0.3. Note that some of these features aren't available in previous versions.  Currently version 0.3 is the development branch.

#Formatting

1. In terms of formatting, please try to use a cookbook-like format...that is:
    
    ###Problem: You want to access data from database.
     
    ###Solution: Use this code...

1. Note that the urls don't need "web" in them -- just "/cookbook/select" , not "/cookbook/web.select".  

1. Finally, this documentation is for version 0.3, so please only add code that you know works with the new version.

-------------------------------------------------

##Basics:
* [Hello World](/cookbook/helloworld)
* [Serving Static Files](/cookbook/staticfiles)
* [Seeother and Redirect](/cookbook/redirect+seeother)

##Advanced
* [web.ctx](/cookbook/ctx)
* loadhooks/unloadhooks (requested)
* How to properly use web.background (requested)

##Sessions and user state:
* [Working with Session](/cookbook/sessions)
* [Working with Cookies](/cookbook/cookies)
* User authentication (requested)

##Utils:
* [Sending Mail](/cookbook/sendmail)

##Templates:
* [Using Site Layout Templates](/cookbook/layout_template)
* Odd/even table rows (requested)

##User Input:
* [File Upload](/cookbook/fileupload)
* [Accessing user input through web.input](/cookbook/input)
* Using basic forms (requested)

##Database:
* Mutliple databases (requested)
* [Select: Retrieving entries from a database](/cookbook/select)
* Update (requested)
* Delete (requested)
* Insert (requested)
* Query (requested)

##Deployment:
* Fastcgi deployment through lighttpd (requested)
* Fastcgi deployment through Apache (requested)
* mod_python deployment through Apache (requested)
* nginx deployment (requested)

