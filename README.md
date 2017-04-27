# PHP Library Database
### Authored by Dylan Stackhouse & Jennifer Beem
# Description
A website to manage a library database. It allows librarians to add/edit/delete books, as well as loan out books to registered patrons.

### Requirements
This site requires some programs and frameworks to be installed on your computer in order to run it locally.
* PHP 5
* Composer
* MAMP/mySQL/Apache
* A terminal shell (apple computers will have this by default)
* A web browser

## Setup
Download or clone the repository from [here](https://github.com/DylanCStack/php-library.git). Then in a terminal shell navigate into the folder and run $`composer install`. Next, there are two options to choose from.

1. Navigate to the web folder and run $`php -S localhost:8000`. Next launch MAMP and start a mySQL server.  Finally, navigate to [localhost:8000](http://localhost:8000) in your web browser of choice.
2. Launch MAMP navigate to MAMP>Preferences>Web Server>Document Root and set the path to the web folder in the project. Then navigate to [localhost:8888](http://localhost:8888).
