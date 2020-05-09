# DESCRIPTION

Implemented RESTful web service which displays customer records. 
UI design includes navigation tab which include Home, Order List and Product. 
Home tab displays the list of customers along with Customer name, Product ID and Item Price.  
Order List displays list of orders including Order ID, Order Status, Tracking ID of order and date when order is placed. 
# Running the App

1. Click on the Clone the file and download the zip
2. Create a folder and extract files in the folder
3. Install node
4. Navigate to the root directory from CMD
5. Run the command npm install 
6. Run the command node index 
7. Install the docker toolbox
8. Navigate to root directory from CMD. 
9. Run the command docker build -t project-node .
10. Run the command docker run -d -p 1200:1200 project-node
11. Copy the IP address from docker toolbox and paste in browser alongwith assigned port number.
