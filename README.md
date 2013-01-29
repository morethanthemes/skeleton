Skeleton
==============

This repository contains the Drupal installation that runs at [drupalizing.com](http://drupalizing.com) and demonstrates the [“Skeleton”](http://drupal.org/project/skeletontheme) Drupal theme. We use this repository in order to maintain the above mentioned site and develop the corresponding theme. 

You are welcome however to grab this code and have the demonstration site running on your end. By doing this you have the chance to see the ["Skeleton" theme in action](http://demo.drupalizing.com/?theme=skeleton) exactly the way it looks like on our demo.

Installation instructions
--------------
+ Checkout this repository and place the “site” folder under your apache path. 
+ Create an empty MySQL database and import there the “db_instances/corkedscrewer.sql” file.
+ Edit the “sites/default/settings.php” file and point the drupal installation to the newly created database.

Now you are ready to login to the demonstration site by following the URL where your apache is serving the “sites” folder. 

Login to this site by using the following credentials:
- u: admin
- p: password