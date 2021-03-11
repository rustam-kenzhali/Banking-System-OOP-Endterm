# java_endterm_project
# Banking System

As a project task, we created an online banking system. You can use it as a manager or user. All information sent and taken from the database at PostgreSQL

![alt text](https://github.com/rustam-kenzhali/OOP-EdntermProject-CS--Team4-CS_2006/blob/main/Снимок.PNG?raw=true)

At the beginning we choose who we are user or manager
Choosing a user, we can either create an account or log in to an existing one. You can't create two identical accounts. Before registration, the entered data is compared with all the data from the database. If we enter incorrect data, the code in the console will issue a warning. And ask if we want to continue or not

User options: 
1. Can create a new bank card. Note: each user can have only one bank card. If we want to create a new one the code will give a warning that the user already has a card
2. We can find out the number and balance of your bank card
3. We can add money. Although this is incorrect. This was done to check the performance of actions with money
4. The user can make a transfer of money from his card to the card of another user by phone number
5. The user can delete their card
6. The user can send a question to the manager. In the future I will update it so that the manager can return the answer to this question
7. The user can delete their account. To do this, a request with the reason will be sent to the manager. If the manager approves then all information about this user will be completely removed from the entire code

When choosing a manager, we can only log in to an already created account. Only the director has the right to create a new account. Other managers don't have this feature
Managers option:
1. The manager can delete the account of the user who sent the deletion request
2. The manager can view the questions sent by the user. In the future, the function of answering the question will be added
3. If this is the boss then he can add a new manager to the system
