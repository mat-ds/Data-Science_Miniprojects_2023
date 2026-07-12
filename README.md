# Data-Science_Miniprojects_2023

(1) Webscraping - Examining the NYC Socialite Network
The New York Social Diary provides a fascinating lens onto New York's socially well-to-do. As shown in this report of a holiday party, almost all the photos have annotated captions labeling their subjects. We can think of this as an implied social graph: there is a connection between two individuals if they appear in a picture together.

Methodologically this was completed by using BeautifulSoup to scrape website pages for photo captions up to a date cut off, a total of ~93,000. These captions were then parsed to return unique names, revealing a total of ~110,000 nodes in the social network. The structure of this social network was analyzed via node degrees and pagerank algorithm. From this popularity and influence can be gaged, and strength of connections (spouse, friends, family) can be proxied.

TOOLS USED: Python - BeautifulSoup, regex, networkx, matplotlib

(2) Machine Learning - Predicting Yelp Ratings
The Yelp dataset contains unstructured meta data about each venue (city, latitude/longitude, category descriptions, etc), and a star rating. Predicting a new venue's popularity from such information makes for a great ML problem. It had all the classics from data wrangling in JSON, feature engineering, creating custom transformer in the ML pipeline, to an ensemble regressor

TOOLS USED: numpy, pandas, sklearn

(3) Image Classification with TensorFlow
