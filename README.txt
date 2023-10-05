Shop Finding and Navigation System

Overview

A Python application entitled the Shop Finding and Navigation System was created to assist users rapidly locate shops in a shopping center. Furthermore, this program has features for managing store data, such as categories and ratings.

Files
- shop_navigation_system.ipynb: The Shop Navigation System's primary implementation can be located in this file. It has classes and procedures for creating shops, looking for shops based on categories, maintaining store data, and dealing with real-time changes. This acts as the program's entrance point, exhibiting several capabilities and showing how to utilize the system with sample data. a Python script that creates a Graph class that may be used for implementations of Breadth-First Search (BFS) and Depth-First Search (DFS). 

Dependencies
The following Python libraries are utilized by this program:
- NetworkX: A graph-making and graph-analysis library.
- Matplotlib: A library for plotting that is used to display the graph.
- Python 3.x: Python 3.x was used to create the software.

Install Dependencies
- Make sure Python 3.x is set up on computer. The official Python website, https://www.python.org/downloads, is where I may get it. 
- Install the necessary Python packages using pip. 

How to Run
Follow these steps to run the Shop Finding and Navigation System:
1. Clone this repository to local machine:
Git clone --> https://github.com/naheel867/naheelsuleman.git
2. Navigate to the project directory:
   cd shop-navigation-system
3. Run the program using Python:
  Python --> shop-navigation-system.ipynb

Features and Usage
Here are the key functionalities and how to utilize them are listed below:
1. Adding Shops 
- To expand the system's store selection. To add information about a store, such as its number, name, category, location, and rating, use the 'add_shop' function found in the 'ShopNavigationSystem' class.
2. Looking for Stores by Category
 - To look for stores by category, use the'search_by_category' function. To get a list of stores in that category, pass the desired category as an argument to this function.
3. Sorting businesses by Ratings
 - To arrange businesses according to customer reviews inside each category, the software uses a max-heap data structure. With the 'extract_sorted_shops_by_rating' method, shops are extracted and presented in decreasing order of ratings. Get a list of the best stores in a particular category using this strategy.
4. Displaying Shop Information 
– To display specific shop information in-depth, use the 'display_shop_info' function. To show store information, pass the shop number as an argument to this method.
5. Listing All Available store Categories 
- To list every available store category, use the 'display_all_categories' function. An overview of the categories in which stores are offered is provided by this manner.
6. Interact with the Program: 
After the program has begun to run, it may interact with it by doing what are told. It may add stores, make boundaries connecting them, locate pathways, and contrast the outcomes of DFS and BFS.
7. Visualization:
In addition, the application will exhibit a directed graph with links between shops.

Usage
This shop navigation system may be used as a starting point for navigation solutions in shopping centers and other similar settings. The shop's details, categories, and locations may all be changed as necessary.

Contributors
[Naheel Suleman] (https://github.com/naheel867): Sole contributor to the project
