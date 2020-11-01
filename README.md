# Bank-Management-System
Bank management sytem written in c

-Developed with the help of system calls 
-implements locking mechanism to handle crictical section
-uses socket programming for communication between server and client



# How to use->
To start the server, use
$ gcc server.c -o server
$ ./server <port-no>


to start the client, use
$ gcc client.c -o client
$ ./client <port-no entered in server>

If error at bind occurs try with different port number


ADMIN DETAILS-
username- admin
password- password



//Some Information about files
Accounts.dat file used to store data of individual accounts 
structure->
Name,password,acc_id(account_id),active(This will tell if the account exists or not)

Joint_Account.dat File is used to store information about joint accounts
structure->
username1,username2,password1,password2,acc_id(account_id),active


