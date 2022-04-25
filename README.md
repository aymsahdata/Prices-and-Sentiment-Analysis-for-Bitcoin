<div align="center">
      <h1> <img src="https://i.imgur.com/SK0kuMu.png" width="80px"><br/>Bitcoin Sentiment & Price Analysis</h1>
     </div>


# Description
A project on identifiyng future bitcoin prices, analyzing sentiment of bitcoin from Twitter and Ajman University students

# Features
In this notebook there are three datasets:

The first one is about bitcoin prices where we discuss the prices of bitcoin over the years.
The second one is about the sentiment analysis where we have a look at what people think about bitcoin.
The third and last dataset is a simple dataset taken from a survey we made for Ajman University (AU) students to see what they think of Bitcoin.

The outcomes of this project:

To ensure that our audience have good understanding of what Bitcoin is.
Give them a glimpse of the huge world of cryptocurrencies and how certain things can be a bit opinionated from different perspectives.


# Tech Used
 ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
      
# Instructions:

### [---> Link to Project on Google Colab <---](https://colab.research.google.com/drive/1Mb4o_-rHkEKSHxqNxb5QG34vl8nLi3tJ?usp=sharing)

### Loading Files & Libraries in Colab:
- First, change runtime type to GPU Acceleration through the "Runtime" tab under the name of the project in the top left and then selecting "Change runtime type" and changing the Hardware accelerator to "GPU":
![](https://i.imgur.com/4FvdMWk.png)

- Then, connect to the runtime using the "Connect" button on the right and proceed to import all libraries by running the cells in the "importing libraries that we are going to use" section:
![](https://i.imgur.com/alRR4xS.png)

- Now for adding the required csv files, simply click on the folder button on the left side of the screen and drag in the files:
![](https://i.imgur.com/euIc4Ok.png)  then click "OK" on the prompt that shows up on the screen.

----

### Usage of Libraries/Imports
| Library | Usage |
| ----------- | ----------- |
| Pycaret | Used for attribute selection and model rating/performance based on given data. |
| Plotly GO | Plotly's Graph Object (GO) was used for in-depth data visualization of our Bitcoin datasets. |
| Plotly EX | Plotly Express (EX) is a 'syntax-truncated' version of Plotly's GO, for ease of use on more simple visualization tasks.|
| TextBlob | Used for text analysis and sentiment score acquisition. |
| NLTK | Used for reading corpus files for stopword removal in textual data. |
