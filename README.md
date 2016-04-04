# OnlineBookStore
It is a online book store sample built by JavaEE, running on a tomcat 8.

Upon importing the WAR file, create one database connection to the project database, located in the project's
WebContent folder (database is called DB), and create another database connection to the testing database
(called testDB in the WebContent folder of WinterProjectTest). Then, go into the context.xml file (located in
the WebContent folder) and change the location of the database to the url found in the Properties section of
the given database connection. If the project database cannot be created, then it is possible to create the
database in any desired location. Use the creation script and then set the location of the database in the
context.xml file to the correct filepath.

Please note that the JUnit 4 library must be added to the JavaBuild Path of the project
Right click on the Java Project, Properties, Java Build Path, click the "Libraries" tab.
Click "Add Library", JUnit, Next, then choose JUnit4 for the "JUnit Library Version".
Click "Finish", "Ok".

Administrator URL:http://localhost:8080/WinterProject/Admin
Admin Account Info:
username: Admin
password: Admin

Partner URL:http://localhost:8080/WinterProject/Partner
Partner Account Info:
username: Partner
password: Partner

MainPage URL:http://localhost:8080/WinterProject/Start

 Make sure your project has a JAX-RS facet (right click your project and go to properties, verify the JAX-RS is checked under project facets)
