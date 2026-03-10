# JSON Social Data Analysis

This project focuses on cleaning, processing, and analyzing social network data stored in JSON format using Advanced Python. The dataset represents a simplified social media structure containing information about users, their friendships, and the pages they follow or like.

The primary objective of this project is to demonstrate how raw JSON data can be cleaned and transformed into structured information that can be used to generate meaningful insights. The project implements logic to filter and identify potential recommendations such as **"People You May Know"** and **"Pages You May Like"** by analyzing existing user connections and shared page interests.

The dataset includes two main components: users and pages. Each user has a unique identifier, a name, a list of friend connections, and a list of pages they like. The pages section contains page identifiers and page names representing communities or interest groups. By examining these relationships, the project explores how recommendation patterns can be derived from social data.

The development and analysis were performed using **Python within JupyterLab in the Anaconda environment**, which provides an interactive workspace for exploring datasets, running Python scripts, and testing data processing logic step by step.

This project demonstrates the use of several advanced Python programming concepts, including:

* JSON parsing and structured data extraction
* Dictionary and list manipulation
* Set operations for identifying mutual relationships
* Data cleaning and preprocessing techniques
* Logical filtering to generate recommendation candidates
* Efficient data traversal and processing using Python

Key functionalities implemented in this project include:

* Loading and parsing JSON data files
* Cleaning and organizing user and page data
* Identifying mutual friends between users
* Filtering potential "People You May Know" suggestions
* Recommending pages based on common interests
* Analyzing relationships between users and social communities

Tools and technologies used in this project:

* Python (Advanced Python programming concepts)
* JSON data structures
* Anaconda Prompt for environment management
* JupyterLab for interactive data exploration and analysis

This project highlights how Python can be effectively used for **data cleaning, data processing, and simple recommendation system analysis** without relying on external data analysis libraries. It also demonstrates foundational concepts used in **social network analysis and recommendation systems**, which are widely applied in modern social media platforms.
