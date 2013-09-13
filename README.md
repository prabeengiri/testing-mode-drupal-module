testing_mode
============

Testing Mode (Drupal Module)

This module switches the database for the simpletest framework can use which won't alter anything on the existing database 

To run this effeciently , 


1. you need to have $this->setup = true; on 'setUp' method of Test Class

2. Mysql should exist on the Environment path as it runs the 'mysql' command 
3. Drupal command is under the plan


