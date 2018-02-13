# Website
The GodSpeak website at http:givegodspeak.com is a WordPress site. For the impact map, the WordPress site uses an iFrame that points to a web page on “go.givegodspeak.com.”

The WordPress install uses a editor plugin that allows the developer to change the look and feel of the app inside the WordPress dashboard.

The hosting at Name.com is paid until April 8th 2018. It’s about $203/year. 

We can deliver a MySql backup and WordPress files to be transferred to another host.

There are no analytics for the website outside of what WordPress may report in its dashboard.

# Dashboard (Portal)/Mobile REST API
go.givegodspeak.com is an ASP.NET website and REST API that is hosted at Azure. I believe at this time Venado is pending $50/month on the web api hosting. This is paid monthly. 

The dashboard and API are both written using C# and ASP.NET MVC. This site can be hosted on any host that can run ASP.NET MVC with SQL Server. All data can be exported to a new SQL Server host as well. This site can also be transferred to another Azure account which would be the recommended course of action.

Outside of the server health statistics provided in the Azure dashboard, there are no analytics for the Dashboard.

# Mobile Application
The mobile application is written with Xamarin.Forms using MvvmCross for the architecture. 

The app reports crashes as well as submitted bug reports to HockeyApp. Ownership of this account can be transferred to another HockeyApp account.

There are no analytics for the mobile app.

# Source Code
Source code for both the Dashboard and Mobile Application are in a GodSpeak's Github repository. 

One note: for the mobile app the iOS code is in branch “master_ios” and the Android code is in the branch “master_android.”


