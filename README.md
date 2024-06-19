# Flask-driven Book Search Engine & Recommendation System with HTML CSS, JS, Wikipedia API & Collaborative-Filtering Using KNN
## OVERVIEW
Wanderlust Reads is a Flask-driven book application that uses Wikipedia API for book searching and techniques like Collaborative Filtering using the KNN model for recommendations. It uses HTML, CSS, and Vanilla JavaScript for the front end. It also has an add-to-cart and ordering books functionality.
# LANDING HOME PAGE

![BOOK RECOMMENDATION   SEARCH ENGINE](https://github.com/areeba0/Book-Search---Recommendation-System-with-HTML-CSS--JS-Wikipedia-API-Flask----Collaborative-Filtering/assets/136759791/301d797b-393e-4f8d-8775-90963b825484)

# KEY FEATURES = 
- Automated Dependency Management: Automatically checks and installs missing Python libraries required for the project.
- Book Search Functionality: Allows users to search for books and retrieve relevant content from Wikipedia.
- Spelling Correction: Corrects user input using a spell checker to improve search accuracy.
- Recommendation System: Recommends books based on similarity using a pre-trained K-Nearest Neighbors (KNN) model.
- Interactive Web Interface: A user-friendly web interface built with Flask, CSS, JavaScript, and HTML.
- Dynamic Content Display: Shows search results, book information, images, and recommendations dynamically.
- Book Order Functionality: The user can add books to the cart, fill out the form, and order the book.
- Data Preprocessing: Cleans and preprocesses input data to ensure accurate search results and recommendations.

# Book Chatbot
This project implements a Book Chatbot that utilizes various libraries and API to provide information about books based on user queries. Below is an overview of its features, functionalities, and how to use it effectively.
## Output Display Example = DEMON SLAYER MANGA :

![image](https://github.com/areeba0/Book-Search---Recommendation-System-with-HTML-CSS--JS-Wikipedia-API-Flask----Collaborative-Filtering/assets/136759791/ba23dcf3-0fb8-40b2-b22e-31d2292af7ed)

![image](https://github.com/areeba0/Book-Search---Recommendation-System-with-HTML-CSS--JS-Wikipedia-API-Flask----Collaborative-Filtering/assets/136759791/0f774d43-f9c5-4fed-9b19-e65262ec7d70)

## Features
### Text Preprocessing:
- Converts user input to lowercase.
- Performs spell-checking and correction for English words using TextBlob and SpellChecker.
  
### Book Information Retrieval:
- Uses wikipedia library to fetch content about a book.
- Extracts relevant sections based on user query using regular expressions.

### Image Retrieval:
- Fetches multiple book cover images from Google Images API using BeautifulSoup for web scraping.
- Downloads and saves the images locally for display.

# Book Recommendation System
## Overview
This project implements a book recommendation system based on collaborative filtering using the k-nearest neighbors algorithm (k-NN). The system recommends books similar to a given book using user ratings data.

![image](https://github.com/areeba0/Book-Search---Recommendation-System-with-HTML-CSS--JS-Wikipedia-API-Flask----Collaborative-Filtering/assets/136759791/232f2f34-282d-42e7-b245-cae4a38fb1a8)

- Book Recommendation: Given a book title, the system recommends similar books based on user ratings.
- Model Persistence: The trained k-NN model and recommendation function are saved using pickle for easy reuse.
- Data Cleaning: The dataset was cleaned to handle CSV file inconsistencies before loading into the system.
- Dataset: Utilizes the Book-Crossings dataset, containing user ratings of books.
### Model Used = 
- Nearest Neighbors Algorithm: The k-NN algorithm with cosine similarity metric.


# Technologies Used
- Flask: A lightweight WSGI web application framework for backend development in Python.
- Python: The core programming language used for backend logic and data processing for search engines and recommendations.
- Jupyter Notebook: Used for initial development and testing of functions and algorithms.
- HTML/CSS: For designing and structuring the front end of the application.
- JavaScript: Adds interactivity to the front end.
- Wikipedia API: For fetching book information and summaries from Wikipedia.

# Dependencies =
The following Python libraries are utilized in this project:

1)  wikipedia-api: Retrieves book information from Wikipedia.
#### Installation: pip install wikipedia-api

2) textblob: Processes textual data, including tokenization and spelling correction.
#### Installation: pip install textblob

3) spellchecker: Performs spelling correction on user input.
#### Installation: pip install pyspellchecker

4) requests: Handles HTTP requests for external APIs and web content.
#### Installation: pip install requests

5) BeautifulSoup: Parses HTML and extracts data from web pages.
#### Installation: pip install beautifulsoup4

6) nbformat: Converts Jupyter Notebook content to Python scripts.
#### Installation: pip install nbformat

7) nbconvert: Exports Jupyter Notebooks to Python scripts.
#### Installation: pip install nbconvert

8) flask: Provides the web framework for the backend.
#### Installation: pip install flask

9) Pillow: Handles image processing tasks.
#### Installation: pip install pillow

10) matplotlib: Creates visualizations and plots.
#### Installation: pip install matplotlib

11) numpy: Supports numerical computations.
#### Installation: pip install numpy

12) pandas: Manages dataframes and preprocessing.
#### Installation: pip install pandas

13) scipy: Provides scientific and technical computing tools.
#### Installation: pip install scipy

14) scikit-learn: Supplies machine learning algorithms for recommendations.
#### Installation: pip install scikit-learn

15) pickle: Serializes and deserializes Python objects.
#### Installation: Comes with the standard library.
  
# NOTE=
The front end for image retrieval and recommendation system has not yet been implemented. Only the backend has been implemented.


