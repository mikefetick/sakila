sakila
======

My Yii Application with the 'Sakila' MySQL database

Programmers’ Log: ISIS Proposal Generator 
9/20/2014 [Mike] Researching: Chapter 7: Using Zii Components (Pages 199-224)
Book: Yii Application Development Cookbook, 2nd Edition
Using data providers, grids, lists, and creating custom grid columns.
Book example: Table: Initial Yii Developers
 
Book example: The Salika Database
Getting ready 
1.	Create a new application using yiic webapp ‘Sakila’, as described in the official guide. 
2.	Download the Sakila database from http://dev.mysql.com/doc/index-other.html and execute the downloaded SQLs (first schema then data). 
3.	Configure the database connection in protected/config/main.php. 
4.	Use Gii to create a model for the film table. 
How to do it... 
1.	Let's start with a view for a grid controller. Create protected/views/grid/ index.php: 
<?php 
      $this->widget('zii.widgets.grid.CGridView', array(
           'dataProvider' => $ dataProvider, ))
?> 
2.	Then create a controller, protected/ controllers/GridController.php: …
 
 
 

 

 
 
 



