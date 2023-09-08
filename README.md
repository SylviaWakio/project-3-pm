# This is a product management system that allows you to add, list, get,
 update, and delete products in a SQLite database.

 To get started, you need to install the following dependencies:

Python 3
 SQLite3

Once you have installed the dependencies, you can clone the repository and
run the following command to start the application:

python main.py

 Usage

The application can be used to perform the following operations:

Add a product: To add a product, you need to provide the name, brand,
 price, and quantity of the product. For example, to add a product called
"iPhone 13", you would run the following command:

python main.py add iPhone 13 Apple 999 1

List products: To list all products, you can run the following command:

 python main.py list

 Get a product: To get a product by ID, you can run the following command:

 python main.py get 1

Update a product: To update a product, you need to provide the ID of the
product, as well as the new name, brand, price, and quantity. For example,
to update the price of the product with ID 1 to $1000, you would run the
 following command:

python main.py update 1 iPhone 13 Apple 1000 1

 Delete a product: To delete a product, you can run the following command:

 python main.py delete 1





# License
#
# This project is licensed under the MIT License.
