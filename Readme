===========================================================
THIS FILE IS OBSOLETE , 
PLEASE CHECK THE REPORT APENDIX FOR COMPLETE INFORMATION
===========================================================

Check List:

1. Tomcat 6.0 ( or newer )
2. Postgres SQL 8.4
3. Java JRE 6.0
4. Java JDK 1.6
5. Libraries  .Check "./libraries/libraries.txt" for the jar files needed . They can be found in the school netwrok but I don't exactly know where.
( for LG lab they are marked with by network drive "J" )

The library files can also be found in the application's subfolder "./EchoGameWebApp/build/web/WEB-INF/lib"
but have to be copied to a seperate location before adding them to the project.

6. IDE USED: Netbeans 6.0 but you can use any other IDE


How to use

1. Configuring the webapplication: 
   Open "./EchoGameWebApp/src/java/applicationContext.xml". 
   Lines :
     
   22     <property name="url" value="jdbc:postgresql://localhost:5432/EchoGame"/>   Set the location of your database here
   23     <property name="username" value="postgres"/>                               Set username for accesing database here
   24     <property name="password" ref="password" />                                Will open a dialog window and ask for database password

If you want to stop the application from nagging you for a database password on each run you can do the folowing :

        1.1. Comment out or delete line 

                17    <bean id="password" class="Main factory-method="getPassword" />
	
	An the replace current line 24 from

 	              <property name="password" ref="password" />

	              TO

                      <property name="password" value="<<put_password_here>>" />

2. Creating the DataBase

After oppening the project in netbeans or favorite IDE run the "Main.java" file.
 Click "yes" to create the database.
 Click "no" to delete the database.
NOTE: when updates to the application are made you'll have to delete the old database ( by running Main.java of the old application)
and create the new database ( by running Main.java in the new application)


3. Run the application
 You are ready to go. You can run the webapplication from Netbeans now.
 I will add instructions on how to deploy the application to tomcat directly without the need of an IDE.



