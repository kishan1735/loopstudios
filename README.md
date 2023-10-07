|End Point| Methods | Description | Access |
|---|---|---|---|
| {{url}}|  | Display a basic overview of the webpage and contains links to other pages| Everyone |
| {{url}}/account/signup |  | Handles the signup functionality client side | User who is not logged in |
| {{url}}/api/account/signup | POST | Handles the signup funtionality server side and adds the user to the database|  |
| {{url}}/account/login |  | Handle the login functionality client side | User who is not logged in |
| {{url}}/api/account/login | POST | Handles the login funtionality server side|  |
| {{url}}/api/auth/[...nextauth] |  | Handles Next Auth related functionalities|  |
| {{url}}/user/:id/profile |  | Displays data about the user, user purchase and selling history | User who is logged in |
| {{url}}/api/user/:id/profile | GET, PATCH, DELETE | Gets the logged in User from the Database by id, purchase history. Provides functionality to update,delete user  |  |
| {[url}}/user/:id/wallet |  | Display the BITScoin balance,transaction history | User who is logged In |
| {[url}}/api/user/:id/wallet | GET | Gets the BITScoin balance,transaction history from Database |  |
| {{url}}/user/:id/chat |  | Implements the chat functionality | User who is logged In |
| {{url}}/api/user/:id/chat | GET, POST, PATCH, DELETE | Implements the chat functionality server side |  |
| {{url}}/user/chat/:roomId |  | Chat room with random user | User who is logged In |
| {{url}}/user/chat/:roomId | GET, POST, PATCH, DELETE  | Chat room with random user | |
| {{url}}/products | | Displays all the products being auctioned | Everyone but bid and sell buttons is limited to logged in users |
| {{url}}/api/products | GET | Gets products being sold from database |  |
| {{url}}/products/sell/:id| | Functionality to put an item for auction and update data | User who is logged in |
| {{url}}/api/products/sell/:id| POST, PATCH | Adds the posted item to database and updates data |  |
| {{url}/products/:randomId/:name | | View Item being sold and allows u to bid and redirects u to the chat functionality | User who is logged In |
| {{url}/api/products/:randomId/:name | POST | Posts the bid to the data base |  |
