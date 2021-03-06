## AngularJS SPA Template for Visual Studio

This project is a skeleton for a simple single-page web application (SPA) built on top of the:

 - [ASP.NET Web Pages](http://www.asp.net/web-pages) (Razor) 3.0
 - [AngularJS](http://www.angularjs.org) 1.2 RC3 - JavaScript Framework
 - [Bootstrap](http://getbootstrap.com/) 3.0.1 - CSS Framework (based on [LESS](http://lesscss.org/))

You can use it to quickly bootstrap your AngularJS web app projects and dev environment for these projects.

Just clone the repo, open solution file from the ```Source``` folder and you are ready to develop
and test your application.

### Development Environment

 - [Visual Studio 2013](http://www.visualstudio.com) with extension(s):
   - [Web Essentials 2013](http://visualstudiogallery.msdn.microsoft.com/56633663-6799-41d7-9df7-0f2a504ca361)

*Hint: make sure that you have the latest version and updates for Visual Studio and required extensions installed*

### Getting Started

To clone the repo run:

    git clone -o base git@github.com:kriasoft/AngularJS-SPA-Template.git MyApp

Where ```MyApp``` is your project name. Then rename the included solution file:

    git mv Source/Application.sln Source/MyApp.sln
    git add .
    git commit -m 'Rename Application.sln file'

Open ```MyApp.sln``` in Visual Studio and you are ready to go.

Later on you can always pull and merge the latest changes from [AngularJS SPA Template](https://github.com/kriasoft/AngularJS-SPA-Template)
repo into your project by running the following commands:

    git fetch base
    # Fetches any new changes from the AngularJS SPA Template repository (base)
    git merge base/master
    # Merges any changes fetched into your working files

### Contacts

Have questions or need help? Email me at [hello@tarkus.me](mailto:hello@tarkus.me)