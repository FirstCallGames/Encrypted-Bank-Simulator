# Encrypted-Bank-Simulator
This Encrypted Bank Simulator simluates the working of a banking system. It has the options of withdrawal , deposit and checking balance. To protect the information of user it encrypts any and all the data of the user.

*NOTE TO USE THE BANK SIMULATOR YOU REQUIRE PYTHON AND MYSQL-CONNECTOR*

1) To Install MYSQL-CONNECTOR
   
   Run the following command on Windows/MacOS:- pip install mysql-connector-python

2) Creating Database:
   
  To use the simulator you will have to run the following commands in mysql server:-

  create Database BankDet;
  use BankDet;
  create table UserInfo(Username varchar(100) Primary Key, Password varchar(100), Pin int, Balance int, CardNumber int);

  Or 

  You can run the Database Config file by inserting your database password into it.
