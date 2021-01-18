PROJECT DESCRIPTION
1.	The app provides activities with the help of which the user can complete the following tasks:
    o	The user can add new Inventory
    o	The user can view the product details
    o	The user can edit the product details
    o	See a list of all inventory from the Main Activity
    A combination of multiple actions described above into a single activity has also been used.
    The user navigates between the activities and/or fragments using one or more of the following navigation patterns: Navigation Drawer, View Pager, Up/Back Navigation, or Intents.
2.	In the Main Activity, each list item displays:
    o	Product Name
    o	Price
    o	Quantity.
    Each list item also contains a SaleButton that reduces the total quantity of that particular product by one (include logic so that no negative quantities are displayed).
3.	The Product Detail Layout displays
    o	Product Name
    o	Price
    o	Quantity
    o	Supplier Name
    o	Supplier Phone Number in the database.
    This Layout also contains buttons with the functionality to increase and decrease the available quantity.
    There is also a check in the code to ensure that no negative quantities are displayed.
    The Product Detail Layout contains a button to delete the product record entirely.
    It also contains a button to order from the supplier by enabling the user to contact the supplier via an intent to a phone app using the Supplier Phone Number stored in the database.
    When there is no information to display in the database, the layout displays a TextView with instructions on how to enter values to the database.
4.	The Main Activity contains an Add Product Button prompts the user for product information and supplier information which are then properly stored in the table.
The information given by the user is validated before it is added to the table. Empty product information is not accepted. If user inputs invalid product information (name, price, quantity, supplier name, supplier phone number), the app includes logic to validate that no null values are accepted.
5.	When a user clicks on a List Item from the Main Activity, it opens up the detail screen for the correct product.
6.	In the Detail View for each item, some Buttons correctly increase or decrease the quantity for the correct product.
7.	In the Detail Layout, there is a Delete Button that prompts the user for confirmation and, if confirmed, deletes the product record entirely and sends the user back to the main activity.
 
About Books Box
  User can
    •	Add Book details
(Product Name, Product Price, Product Quantity, Supplier Name, Supplier Contact Number) and successfully adding book will display product name, product price and product quantity on the main screen.
    •	Edit book details.
    •	Delete single book at a time as well as all the books at the same time.
    •	Contact supplier using supplier phone number.
    •	Can decrease the product quantity from the main screen using the "Sale" button attached to each book.
NOTE: All fields are mandatory and must be entered by the user.
