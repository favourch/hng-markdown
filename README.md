
**PHP**

XAMPP is the most popular PHP development environment. XAMPP is an easy to install Apache distribution containing MariaDB, PHP, and Perl. Just download and start the installer. It's that easy.



*   Visit [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html)

Depending on your OS, click on XAMPP for windows, Linux or OS X and follow the instructions that follows.

**Composer**

Composer is a tool for dependency management in PHP. It allows you to declare the dependent libraries your project needs and it will install them in your project for you. It is a dependency manager not a package manager.

**Windows Installer**



*   The installer will download composer for you and set up your PATH environment variable so you can simply call composer from any directory.
*   Download and run [https://getcomposer.org/Composer-Setup.exe](https://getcomposer.org/Composer-Setup.exe) - it will install the latest composer version whenever it is executed.

**Installer Options using command line**



*   CD into --install-dir
*   You can install composer to a specific directory by using the --install-dir option and providing a target directory. 

    **Example:**


        `php composer-setup.php --install-dir=bin`

*   --filename

-  You can specify the filename (default: composer.phar) using the --filename option.       

**Example:**


        `php composer-setup.php --filename=composer`



*   --version

- You can install composer to a specific release by using the --version option and providing a

target release. 

**Example:**


        `php composer-setup.php --version=1.0.0-alpha8`

**Gmail account for login and authentication**

All requests to the Gmail API must be authorized by an authenticated user. Gmail uses the OAuth 2.0 protocol for
authenticating a Google account and authorizing access to user data. You can also use Google+ Sign-in to provide a
"sign-in with Google" authentication method for your app. This is the method of authenticating a user for this application

To create an account using this application, you will need a [Gmail](https://gmail.com) account.

**Troubleshooting**

If you run into issues using the application, kindly check to make sure you have all the dependencies installed and accounted for.
