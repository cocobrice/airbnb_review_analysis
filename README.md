# Project 1: Write a Data Science blog
For this project we pick a dataset and answer 3 questions using the data. The questions I pose are:

1.  Can we use Textblob package to establish the sentiment of text reviews of AirBNB properties in Seattle?
2. What are the common themes of the text reviews of AirBNB properties in Seattle?
3. Can we use the features of an AirBNB property to predict its eventual review sentiment or score?

Contents:
1. [Libraries used](#libraries-used)
2. [Data](#data)
3. [Notebooks](#notebooks)
4. [Blog post](#blog-post)

### **Libraries used**
* numpy == 1.19.2
* pandas == 1.1.3
* matplotlib.pyplot == 3.3.2
* seaborn == 0.11.0
* scikit-learn == 0.23.2
* textblob ==  0.17.1
* wordcloud == 1.8.2.2

### **Data**
|      Data       |             Description                      |                    Source                      |
|-----------------|----------------------------------------------|------------------------------------------------|
|   listings.csv  |   Property descriptions with review scores   | https://www.kaggle.com/datasets/airbnb/seattle |
|   reviews.csv   |   Text reviews of properties                 | https://www.kaggle.com/datasets/airbnb/seattle |

### **Notebooks**
|   Notebook      | Description |
|---|---|
| airbnb.ipynb | This notebook is used for cleaning text, finding commonly used words and phrases, using TextBlob to establish sentiment, cleaning feature data and modelling results |

### **Blog Post**
https://medium.com/@cocobrice3/airbnb-review-sentiment-analysis-da2756a8302f
