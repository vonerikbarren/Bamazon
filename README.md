# Bamazon

## Overview / Description
-  creating an Amazon-like storefront with the MySQL skills you learned this unit. The app will take in orders from customers and deplete stock from the store's inventory. As a bonus task, you can program your app to track product sales across your store's departments and then provide a summary of the highest-grossing departments in the store.


## Pseudocode
1. First create initialize a git repository with README.md
2. clone it to computer
3. move to directory via bash
4. bash: npm init -y to create package.json
5. bash: touch .gitignore
6. mySQL Workbench: Log-in with user credentials
7. mySQL Workbench: create Database called bamazon
8. mySQL Workbench: create a table called products
9. mySQL Workbench: create product table with the items:
   1.  item_id
   2.  product_name
   3.  department_name
   4.  price
   5.  stock_quantity

10. mySQL Workbench: populate the database with 10 different products
11. bash: check for proper directory then touch bamazonCustomer.js
12. code: code with inquirer:
    1.  ask for id of product
    2.  ask for # of units 

13. code: create conditional statements to check to see if there is sufficient products / sufficient funds / sufficient units of product
14. code: if true, update database to show the correlating numbers minus what user wants
15. code: if false, return an update to user that one of the 3 is insufficent 



16. bash: touch bamazonManager.js 
17. code: code with inquirer:
    1.  List set of menu options
        1.  view products for sale
        2.  view low inventory
        3.  add to inventory
        4.  add new product 

18. code: create more conditional statements where if the user selects any of these options, then it runs a function correlating to each.
    1.  if user selects "view products for sale" , it would view the item ID, names, prices, and quantities
    2.  if user selects "view low inventory", it would view the items that have an inventory less than 5
    3.  if user selects "add to inventory", it would prompt the user to add more of any item currently in the store
    4.  if user selects "add new product", it would allow user to create a new product to the store 
