# Discover Pane Template
[![As-Is](https://img.shields.io/badge/Support%20Level-As--Is-e8762c.svg)](https://www.tableau.com/support-levels-it-and-developer-tools)

This repository contains a template for customizing the Tableau Desktop Discover Pane.
The Discover Pane is part of start page of Tableau Desktop, specifically the right side pane which is loaded from a website.
![alt text](https://help.tableau.com/current/pro/desktop/en-us/Img/environment_startpage.png "Tableau Desktop Start Page")
If you are planning to provide your own content for this pane, the HTML file in this respository can be used on a webserver (provided by you) to give a similar experience to the existing Discover Pane.  Additionally you can modify the HTML with your own links.  You will need to [configure Tableau Desktop to use the URL that points to the web url hosting this html](https://help.tableau.com/v2020.1/desktopdeploy/en-us/desktop_deploy_setting_changes.htm).


### Requirements:
* A webserver that hosts the html file ([IIS](https://www.iis.net), [Apache](https://httpd.apache.org), [Nginx](https://www.nginx.com), etc.)
* Tableau Desktop (v2020.1 or higher) configured to point to the URL of the HTML on the webserver
* For best results don’t use web pages that include javascript or redirects
