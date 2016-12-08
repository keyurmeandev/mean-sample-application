Installation Guide for MEAN-stack sample application
----------------------------------------------------
1. Place the folder to desired location
2. Start command line and go to the root. Make sure you are at same location where
   package.json file is.
3. run command > npm install
   It will add all dependent modules which are required by app and server
4. config.json file is used to connect mongodb and to store config variables.
5. Installation guide and using of Database is describe at the bottom.
6. run > node server.js command
7. Use the app with login and registration


MongoDB Installation Guide for windows
1) Download latest installation package from mongodb website and install it.

2) As Admin, create directory:
    mkdir c:\mongo\data\db

3) Go to the path where mongo is installed and
   As Admin, install service:
    .\mongod.exe --install --logpath c:\mongo\logs --logappend --bind_ip 127.0.0.1 --dbpath c:\mongo\data\db --directoryperdb

4) Start MongoDB:
   net start MongoDB

5) Start Mongo Shell:
   c:\mongo\bin\mongo.exe

