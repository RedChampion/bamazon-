# Application

## bamazon

## Description

This is a node application to:
* view product information
* allow customer to place orders for products

## Getting Started

### Prerequsites

1. Node.js must be installed (https://nodejs.org/en/download/)
1. MySQL must be installed. At a minimum, the free Community Edition must be present (https://www.mysql.com/downloads/) 
1. A MySQL developer tool such as MySQL Workbench or Sequel Pro (https://dev.mysql.com/downloads/workbench/) is needed to create and seed the database

### Installation

1. Clone repository bamazon using the code -> _git clone https://github.com/RedChampion/bamazon-
1. Open a terminal session for the directory where the application was cloned to
1. run *npm install* to install the dependencies
1. Use the *schema.sql* & *seeds.sql* files to create the databases in MySQL

## Using the Application

### General Instructions

1. You must be in a terminal session for the directory that contains the application
1. Use the up/down arrow keys to navigate through options and lists
1. Select an option or list item by pressing Enter or Return
1. The options and lists generally have an _Exit_ item that can be selected to exit the application
1. Ctrl+c _for windows_ or Command+c _for Mac_ can be used to exit the application at any time

### bamazonCustomer.js

1. run _node server.js_ from a terminal session in the application directory
1. A list of products is presented
1. Select a product id to order
1. Once a product is selected, reply to the prompt with the quantity to order
1. A reply is provided indicating if the order is created or if there is not enough inventory
1. Reply to the prompt to continue with another order or to exit the application

## Technical Information

### Database
1. MySQL is used as the database
2. Details for the database, tables and users can be found in the *.sql files

### Packages
1. cli-table    provides formatting to display list data in a table (https://www.npmjs.com/package/cli-table)
1. inquirer     provides framework for user prompts (https://www.npmjs.com/package/inquirer)
1. mysql        provides connection to MySQL database (https://www.npmjs.com/package/node-mysql)

### Instructions
![](bamazon.gif)