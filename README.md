testing_mode
============

Testing Mode (Drupal Module)

This module changes database for testing and puts the Drupal in the testing mode. 

To run this effeciently , 


1. you need to have $this->setup = true; on 'setUp' method of Test Class

2. Mysql should exist on the Environment path as it runs the 'mysql' command 
3. Drush command is under the plan


