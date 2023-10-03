|End Point| Methods | Description | Access |
|--|--|--|--|
| {{url}}| - | Display a basic overview of the webpage and contains links to other pages| Everyone |
----------------------------------------------------------------------------------------------------
| {{url}}/account/signup | - | Handles the signup functionality client side | User who is not logged in |
--------------------------------------------------------------------------------------------------------
| {{url}}/api/account/signup | POST | Handles the signup funtionality server side and adds the user to the database| API endpoint |
-----------------------------------------------------------------------------------------------------------------------------------
| {{url}}/account/login | - | Handle the login functionality client side | User who is not logged in |
------------------------------------------------------------------------------------------------------
| {{url}}/api/account/signup | POST | Handles the login funtionality server side| API endpoint |
------------------------------------------------------------------------------------------------
| {{url}}/user/:id/profile | - | Displays data about the user, user purchase and selling history | User who is logged in |
-------------------------------------------------------------------------------------------------
| {{url}}/api/user/:id/profile | GET, PATCH ,DELETE | Gets the logged in User from the Database by id, purchase history. Provides functionality to update,delete user  | API Endpoint |
---------------------------------------------------------------------------------------------------------
| {[url}}/user/:id/wallet | - | Display the BITScoin balance,transaction history | User who is logged In |
----------------------------------------------------------------------------------------------------------
| {[url}}/api/user/:id/wallet | GET | Gets the BITScoin balance,transaction history from Database | API endpoint |
---------------------------------------------------------------------------------------------------------------------
| {{url}}/user/:id/chat | - | Implements the chat functionality | User who is logged In |
-----------------------------------------------------------------------------------------
| {{url}}/api/user/:id/chat | GET, POST, PATCH, DELETE | Implements the chat functionality server side | User who is logged In |
-------------------------------------------------------------------------------------------------------------------------------
| {{url}}/api/products | - | Displays all the products being auctioned | Everyone but purchasing is limited to logged in users |
--------------------------------------------------------------------------------------------------------------------------------
