# Perceptron algorithm for 2 and 3 dimension problems
 I make use of MySQL, specifically phpMyAdmin to munipulate data. So after you have downloaded the project in order to run the code you shall have installed a server that supports MySQL and phpMyAdmin like XAMPP, MAMP etc. I personally prefer XAMPP as i find it more convinient to use.

 It is very easy to load data from the server.<br> 
 - Step 1 <br/>
 After XAMPP installation. Start the apache server and MySQL database. <br/> <br/>
 ![Screenshot (6)](https://user-images.githubusercontent.com/109686747/184480651-c7da150f-5cab-40de-b3bc-d40f29f689da.png)
- Step 2 <br/>
  In your browser url type address : <br/> <br/>
  localhost/phpmyadmin/ <br/> <br/>
  This action while open the phpMyAdmin panel. <br/> <br/>
  ![Screenshot (7)](https://user-images.githubusercontent.com/109686747/184489989-8f09840c-0198-4f15-95ac-1279c07f02c3.png)

   Inside project there is a "data" folder and inside that folder the <u>perceptron.sql</u> file. This file creates some tables containing all the data_set needed for the perceptron training.
- Step 3 <br>
  From phpMyAdmin panel:
    - Create a new database and name it perceptron
    - Choose the percetron database -> push import button
    - From file to import -> choose file ( perceptron.sql ) -> import

 Now your database should be ready to use.
 
 In order to run the code: 
   - From the terminal cd to the project path where Perceptron2D.py and Perceptron3D.py are placed  
   Type:
   
     python perceptron_2d.py <br/>
   or <br/>
     python perceptron_3d.py
   
   Voilà!!!  
   That's it...


