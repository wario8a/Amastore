# Amastore
AmaStore is an Online Store that sells products to customers, it has two types of user administrators and customers

## Requirements
The Application:
- Console Application when an user can select if it is an administrator or customer ([Use Spectre.console](https://github.com/spectreconsole/spectre.console))
- The application must keep register of products bought, inventory, invoice by user and users register. (Use plain text to store the information)
- Must allow multiple users working concurrently
- Show the shopping car for customers

Tha Admistrator can do the next actions:
- Create Users (Administrators)
- Create / Update/ Delete / Read Products
- List the products by department with the all the related information

The customers can do the next actions:
- Add / Remove products to a shopping car.
- Create a Checkout Action (Buy the pructs).
- List all the orders generate.
- When an user enters as a customer it must enter the name. If the customer is new start a new session otherwise continue with the previous session
  
Products
- Name
- Price
- Department
- Quantity
- Date Creation
- Date Updated
- Administrator

Administrator
- Name
- Last Name
- Address
- Phone
- email
- Company
- Date of joining
- Supervisor Name
- Date Creation
- Date Updated
- Created By
  
Customer
- Name
- Last Name
- Address
- Phone
- email
- Credit Card Number
- Amount of money avaliable
- Date Creation
- Date Updated