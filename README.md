# DISTRIBUTED-BANKING-SYSTEM
The Distributed Banking System is a client-server program which is implemented using RMI (Remote Method Invocation).
The server manages all users’ account information.
A customer can invoke the following operations at an ATM:
void deposit(int acnt, int amt): This operation increases the balance of user account acnt by amt and returns nothing
void withdraw(int acnt, int amt): this operation decreases the balance of user account acnt by amt and returns nothing.
float inquiry(int acnt): this operation returns the balance of user account acnt.
The server can only handle one client request at a time in this client-server program. 
