# BookStoreBackendE
BookStoreBackendE - This project using Eclipse IDE

Please folow these steps in order to configure your Local Eclipse Environment

1.- Download plug-in by glassfish 5.x
https://projects.eclipse.org/projects/webtools.glassfish-tools/downloads

2.- Unzip zip file 

3.- Go to Eclipse IDE options help-->install new software -->add -->select Archive (select download glassfish plug-in unzip) add plug-in name "glassfish 5.x" -->finish (install glassfish 5.x plug-in)

4.-Download Apache Derby 
http://db.apache.org/derby/releases/release-10.14.2.0.cgi

5.- Unzip file

6.- Open a terminal and execute the next command - run apache derby DB 
(please execute the command in your path/db-derby-10.14.2.0-bin/bin)
$ ./startNetworkServer  or $ startNetworkServer.bat
Security manager installed using the Basic server security policy. 
Apache Derby Network Server - 10.14.2.0 - (1828579) started and ready to accept connections on port 1527

7.- Go to eclipse IDE options window -->show view -->Data Source explorer
Click new -> Derby -->please fill out database, host, pornumber, user, pass, Driver -->Derby Client JDBC Driver --> add JDBC JAR derbyclient.jar (This jar is on your path/db-derby-10.14.2.0-bin/lib/derbyclient.jar

8.- Click in Apache Derby connection --> connect --> after that / open script.sql -->

9.- Please configure Connection file --> Type=Derby_10x name=Apache Derby database=bookstoredb

10.- Execute queries using -->Execute Selected Text

11.- You can Run BookStoreBackendE --> as Run on Server -->using glassfish 5.x and select path/glassfish-5.1.0/bin
Log in your console:
 $-Portable JNDI names for EJB BookstoreDAO: [java:global/BookStoreBackendE/BookstoreDAO
 $-Portable JNDI names for EJB BookstoreShoppingCart: [java:global/BookStoreBackendE/BookstoreShoppingCart

12.- Enjoy it =)




