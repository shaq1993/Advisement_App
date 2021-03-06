# Advise Me! 

Costaatt Advisement Web Application
 
## Getting Started

### Prerequisites

* [WAMP](http://www.wampserver.com/en/) or [AMPPS](https://www.ampps.com/)
* [Composer](https://getcomposer.org/)
* [Twig](https://twig.symfony.com/) (installs with Composer)

### Installing

1. Create branches in your www directory. This will create a folder called Advisement_App
2. Open Command Prompt or Terminal and change directory to Advisement_App folder
3. Run the command ```composer install --no-dev ```
4. Ensure that at least **PHP version 7.0.0** is being used.  

*refer to chapter 6 for more on Composer*

## Guidelines for developers

* Create branches, merges will be decided in class or group discussion.
* Feel free to create issues for feature requests, bug fixes and basically anything.
* Twig and other dependencies is installed into a vendor folder, git will ignore this folder when you commit.
* 'logs' folder should remain empty

## Deployment
Things to remember:

* Set public folder to be root folder.
* In ```Config.php```, set errors to be logged or ignored.
* If error logging is enabled, clear log folder on occasion.
* In ```Config.php```, set database connection information. 
* For database, don't use root username or blank password.
* Database import file located in sql folder
* Enable twig cache in ```Core/View.php``` for speed up.


## Teams

* SQL Queries: Stacy, Kafra, Derek
* DB Design: Katrina, Amanda
* CSS Design: Shaquille, Adrien, Nicholas
* Supervisor: Earl


## License
see LICENSE.md for details
