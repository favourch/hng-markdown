# hng-markdown

## PHP

XAMPP is the most popular PHP development environmet. XAMPP is an easy to install Apache distribution containing MariaDB, PHP, and Perl. Just download and start the installer. It's that easy.

Visit [Apache's Offcial Website to download](https://www.apachefriends.org/index.html)
    
Depending on your OS, click on XAMPP for windows, Linux or OS X and follow the instructions that follows.

## Composer
Composer is a tool for dependency management in PHP. It allows you to declare the dependent libraries your project needs and it will install them in your project for you. It is a dependency manager not a package manager.

 • Windows Installer
  
   - The installer will download composer for you and set up your PATH environment variable so you can simply call composer from any directory.
        
Download and run [https://getcomposer.org/Composer-Setup.exe](https://getcomposer.org/Composer-Setup.exe) - it will install the latest composer version whenever it is executed.

ttttttttttttttttttttttttttttttt

# App Overview

This is a self hosted blogging network i.e. it runs on a domain/url like markessien.com. It allows users to write blog posts and publish them if they are authenticated, this means users of this self hosted blogging site must authenticate their account with a valid gmail account.

Users of this blogging network will be able to follow each other and read blog post of their networks via RSS.

# App Features

The following are the features of the HNG5 Web-App:

- User Account and Profile
- LogIn Authentication
- Homepage with Timeline
- Post Sharing and Saving feature
- RSS Feed
- Commenting Feature
- Option for different themes.

**User Account and Profile:**

The HNG5 Web-app has user account feature that enables users sign up and create personal accounts on the HNG5 website. With this, the user is able to use the website and also connect with other users on the site. This allows the users feel a sense of privacy and building a community on the site.

**Login and Authentication:**

The Login Authentication feature in the HNG5 Web-App enables a secure channel to the users account and profile. With this a user is sure that all their uploaded contents and settings are safely guided and protected

**Homepage and Timeline:**

The Homepage and Timeline on HNG5 Web-app brings to a user a record and activity history of what other users what him/her to see, this includes a new blog post, shared posts, comments and so on. The timeline keeps the user updated with information from other users.



**Post Sharing and Saving:**

On the homepage is a &quot;Write-box&quot; that enables a user craft their own content and post. Below a post, there is a &quot;save&quot; button, a user can use to save contents he/she would love to revisit later. Also, a user can simply share their contents or other users publicized contents on other websites or social media by simply clicking on the &quot;share button&quot;.

**RSS Feed:**

HNG5 Web-app generates an RSS Feed that allows users to easily get up to date information from the website without necessarily visiting the website. This aids the user to get the best of updates from the site at all times without being present on the site.

**Commenting:**

To make HNG5 more interactive, there is a commenting feature that allows a user enable &quot;comments&quot; on the content he/she shares to allow other users react or air their opinions as regards to that specific content. With this people can easily respond to other people&#39;s content.

**Theme Choice:**

HNG5 is built with a default theme and a feature that allows the user to select from a range of free themes.. This allows for personalization of the user&#39;s space.

#

# Dependencies

**Bootstrap**

Bootstrap is an open source toolkit for developing with HTML, CSS, and JS. It is the world&#39;s most popular JS, CSS, and HTML framework that is used to develop mobile-first responsive websites.

- **Installation**
  - **oo**** with npm**
    - Install Bootstrap in your Node.js powered apps with the npm package:
    - run &quot;npm install bootstrap&quot;
  - **oo**** with yarn**
    - Install Bootstrap in your Node.js powered apps with the yarn package:
    - run &quot;yarn add bootstrap&quot;
  - **oo**** with CDN**
    - Include the link below in your HTML head element.

**To use Bootstrap as a link in the HTML file:**

- USING THE CDN
  - \&lt;link rel=&quot;stylesheet&quot; href=&quot;https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css&quot; integrity=&quot;sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm&quot; crossorigin=&quot;anonymous&quot;\&gt;
  - \&lt;script src=&quot;https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js&quot; integrity=&quot;sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl&quot; crossorigin=&quot;anonymous&quot;\&gt;\&lt;/script\&gt;

**For Jquery:**

- \&lt;script src=&quot;https://code.jquery.com/jquery-3.2.1.slim.min.js&quot; integrity=&quot;sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN&quot; crossorigin=&quot;anonymous&quot;\&gt;\&lt;/script\&gt;
- \&lt;script src=&quot;https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js&quot; integrity=&quot;sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q&quot; crossorigin=&quot;anonymous&quot;\&gt;\&lt;/script\&gt;

**PHP**

XAMPP is the most popular PHP development environmet. XAMPP is an easy to install Apache distribution containing MariaDB, PHP, and Perl. Just download and start the installer. It&#39;s that easy.

- Visit [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html)

Depending on your OS, click on XAMPP for windows, Linux or OS X and follow the instructions that follows.

**Composer**

Composer is a tool for dependency management in PHP. It allows you to declare the dependent libraries your project needs and it will install them in your project for you. It is a dependency manager not a package manager.

- **Windows Installer**
  - **oo** The installer will download composer for you and set up your PATH environment variable so you can simply call composer from any directory.
  - **oo** Download and run [https://getcomposer.org/Composer-Setup.exe](https://getcomposer.org/Composer-Setup.exe) - it will install the latest composer version whenever it is executed.

- **Installer Options using command line**
  - **oo** --install-dir
  - **oo** You can install composer to a specific directory by using the --install-dir option and providing a target directory. Example:

php composer-setup.php --install-dir=bin

- --filename
  - You can specify the filename (default: composer.phar) using the --filename option. Example:

php composer-setup.php --filename=composer

- --version
  - You can install composer to a specific release by using the --version option and providing a target release. Example:

php composer-setup.php --version=1.0.0-alpha8

**Gmail account for login and authentication**

All requests to the Gmail API must be authorized by an authenticated user.

Gmail uses the OAuth 2.0 protocol for authenticating a Google account and authorizing access to user data. You can also use Google+ Sign-in to provide a &quot;sign-in with Google&quot; authentication method for your app. This is the method of authenticating a user for this application

To create an account using this application, you will need

- A valid Gmail account

# Screenshots

**(insert images here)**

##
# Troubleshooting

If you run into issues using the application, kindly check to make sure you have all the dependencies installed and accounted for.
