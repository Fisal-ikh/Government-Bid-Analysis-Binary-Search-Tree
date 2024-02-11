# Government-Bid-Analysis-Binary-Search-Tree
Municipal Bid Data Analysis

This repository contains a console program focused on working with information extracted from a municipal government data feed containing bids submitted for the auction of properties. The assignment involves exploring sorting algorithms by implementing a Binary Search Tree of bids loaded from CSV files.

Data Sets

eBid_Monthly_Sales.csv: Larger set of 12,023 bids.
eBid_Monthly_Sales_Dec_2016.csv: Smaller set of 76 bids.
Assignment Overview

The main goal of this assignment is to implement and test sorting algorithms for the provided bid data. The starter console program allows you to interact with the implemented sorting logic through a menu. The menu options include:

Load Bids: Load bid data from a CSV file.
Display All Bids: Display all loaded bids.
Find Bid
Remove Bid
Exit
Enter choice:

To run the program and test the sorting algorithms:

Clone this repository to your local machine.
Compile the program, including the provided CSV parser (CSVparser.cpp).
Run the compiled executable and interact with the menu, input "1" to load bids first. 
Change the path to your correct path.

cd "/Users/fisalikhmayes/Downloads/CS 300 Binary Search Tree Assignment Student Files/" && g++ BinarySearchTree.cpp -o BinarySearchTree && "/Users/fisalikhmayes/Downloads/CS 300 Binary Search Tree Assignment Student Files/"BinarySearchTree

g++ -std=c++11 BinarySearchTree.cpp CSVparser.cpp -o BinarySearchTree ./BinarySearchTree
