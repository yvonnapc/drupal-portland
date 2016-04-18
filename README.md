# _Portland Info Site_

#### A site about the city of Portland  | April 18, 2016

#### By: Yvonna Contreras & Afton Downey

## Description

Drupal: Portland Info Site. This application was built using Drupal and provided practice in setting up a new Drupal site, getting experience with the Drupal interface, and creating content on the site.

## Prerequisites

You will need the following things properly installed on your computer:
• [Drupal](https://www.drupal.org/project/drupal)
• [MAMP] (https://www.mamp.info/en/)

## Setup/Installation Requirements

1. Open Terminal and clone into this repository: https://github.com/yvonnapc/drupal-portland.git
2. In your browser navigate to ```http://localhost:8888/phpmyadmin```, here is where you can select the Import tab and in the project directory go to ```sites > db-backups > databasename.sql.zip``` and click GO at the bottom of your screen
3. Also in phpmyadmin, recreate the user you created initially in the database (the username and password can be found in the settings.php file)
4. Open MAMP, select ```Preferences```, select ```Web Server``` tab, direct the ```Document Root``` at the top level of your project folder
5. Navigate to ```http://localhost:8888``` where you will use Drupal Interface to configure the website and connect the Databases:<br>
      • Select the "Standard" install, click "Save and Continue"<br>
      • Select "English" as the language, click "Save and Continue"<br>
      • Under the "Set up database" tab, select "MySQL, MariaDB, or equivalent" and then fill in the name of your database, and the username and password you just created in phpMyAdmin<br>
      • On the same tab, click on "Advanced Options". Under "Database host" enter "127.0.0.1" and under "Database port" enter "8889". This allows your Drupal installation to work with an important command line tool named Drush that we will learn about later<br>
      • Then click "Save and Continue". This links your Drupal site to the database - this is not the account you will use to login and administer your site. After this step Drupal may take a moment to configure<br>
      • On the next page, labelled "Configure site", pick a site name (like "My First Drupal Site") and enter your email address. This can be changed later<br>
      • Enter details to create a site maintenance account, and make sure to save this Drupal username and password too with your database username and password. This is the account you will use to log in and administer your Drupal site<br>
      • At the bottom select the country and timezone. Then click "Save and Continue"<br>

## Known Bugs

N/A

## Support and Contact Details

If you have any issues, questions, ideas, or concerns contact us through GitHub. If you would like to make a contribution to the code, feel free to do so and notify me by e-mail.

## Technologies Used

• Drupal
• phpMyAdmin
• PHP
• GIT

## License

Copyright (c) 2016  |  Yvonna Contreras & Afton Downey  |  Epicodus  |  Portland, OR
