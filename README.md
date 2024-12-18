**Search Engine: Domain-based (KU)**

This repository contains a simple Search Engine implemented with https://ku.edu as seed page. It includes components web crawling, text preprocessing, stemming, and a ranking mechanism using the Vector Space Model.
________________________________________
**Features**

- Web Crawler: Fetches web pages for indexing
- Text Preprocessing: Tokenization, stopword removal, and case normalization
- Stemming: Reduces words to their root form
- Vector Space Model: Calculates term weights and ranks relevant documents based on user queries
________________________________________
**Requirements**

- Python 3.x
- Required Libraries: numpy, requests, beautifulsoup4
Install dependencies with:
```
pip install numpy requests beautifulsoup4
```
________________________________________
**Setup and Usage**

1.	Clone the repository:
2.	git clone:
```
https://github.com/SudhaChandrikaY/SearchEngine.git
```
3.	cd SearchEngine
4.	Run the Search Engine:
Execute the application with:
5.	python app.py
6.	Search:
  	- Enter a search query when prompted.
    - The program will output ranked results based on relevance.
________________________________________
**Project Structure**

- WebCrawler.py: Crawls web pages and extracts text.
- PreProcessor.py: Handles text cleaning and stopword removal.
- Stemmer.py: Implements stemming algorithms.
- VectorSpaceModel.py: Processes term weights and query rankings.
- stopwords.txt: A list of stopwords for filtering.
- app.py: Main script to run the search engine.
________________________________________
**Images**

![image](https://github.com/user-attachments/assets/d1f38f8a-5b0c-48a9-ab20-b2ea9669ad27)

![image](https://github.com/user-attachments/assets/2640df6f-2eca-4c07-97e1-d619df1cb1f3)

________________________________________
Author: SudhaChandrikaY


