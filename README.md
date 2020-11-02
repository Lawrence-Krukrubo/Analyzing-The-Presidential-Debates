<h2 align="center">Analyzing The Presidential debates of Trump and Biden</h2>
<p align="center">
    <img src="https://miro.medium.com/max/700/1*rsKDgb44kPoDILywNzTExg.jpeg">
</p>
<h2>Intro:</h2>
<p>
    This Project was done primarily to shed more lights on the responses from President Trump and Vice President Biden, 
    during the Presidential debates on Sept 29th and 22nd Oct 2020.<br>
    The data for this entire project was scraped from <a href="https://www.rev.com/blog/transcripts/donald-trump-joe-biden-1st-presidential-debate-transcript-2020">rev.com</a> 
</p>
<h2>Methodology:</h2>
<p> 
    The Scientific methodology for this project includes the following:-
</p>
<ol>
    <li>Web-Scraping: <em>Via requests and BeautifulSoup libraries</em></li>
    <li>Data cleaning and Pre-processing</li>
    <li>Speech-Percentage Computation</li>
    <li>Lexical-Diversity analysis</li>
    <li>TFIDF Computation</li>
    <li>Text Tokenization</li>
    <li>Stopwords Removal: <em>Via nltk library</em></li>
    <li>Punctuations Removal: <em>Via String library</em></li>
    <li>Text Lemmatization: <em>via nltk WordNetLemmatizer</em></li>
    <li>Sentiments Analysis: <em>Via Microsoft Azure Text-Analytics-Client</em></li>
    <li>Key-Phrase-Extraction: <em>Via Microsoft Azure Text-Analytics-Client</em></li>
    <li>Bayesian Inference</li>
</ol>

<h2>Summary:</h2>
<p>
    * The first debate was on September 29, 2020. It was moderated by Chris Wallace 
    of Fox News.<br>
    * The second debate was originally scheduled for October 15th, but was cancelled 
    due to Trump’s bout of COVID19, and held a week later. After his 
    ‘rather-theatrical-and-spectacular-recovery’. This debate was moderated by 
    Kristen Welker of NBC News.
</p>

<p>
    * Kindly see the analysis within the <b>analysis_dir</b> folder 
    and pay attention to the defined methods and intuition of the analysis.<br>
    * From this exercise, I have been able to compare and contrast Trump and Biden's 
    language style, sentiments, responses to key questions and understanding.<br>
    * This Project gives the American public and the world at large, the rare insights
    to the lexical signature and language structure of President trump and Vice-President Biden.<br>
    * The project also explains some of their responses to Key-Areas such as racism, The US Economy, 
    Health-care, Jobs/Wages/Taxes and The American People. 
</p>

<h3>Blog Post:</h3>
<p>
    As a Top-Writer in Artificial Intelligence, I have taken the time to expressively,
    explain my findings in a conversational and less-technical manner for all. Kindly read
    the post in the <a href="https://medium.com/towards-artificial-intelligence/analyzing-the-presidential-debates-5aaa7b328452">Towards_AI</a> publication in the Medium.
</p>

<h3>Dependencies:</h3>
<p>To Follow along, kindly install/import the following libraries...</p>

* `import numpy as np`
* `import pandas as pd`
* `import matplotlib.pyplot as plt`
* `import seaborn as sns`
* `from pywaffle import Waffle`
* `from PIL import Image`
* `import nltk`
* `from nltk import word_tokenize`
* `nltk.download('stopwords')` # For stopwords removal
* `nltk.download('punkt')`  # for tokenization
* `from nltk.corpus import stopwords`
*`from nltk import WordNetLemmatizer`  # To lemmatize sentences
* `nltk.download('wordnet')`
* `from nltk.stem.porter import PorterStemmer`
* `from wordcloud import WordCloud`
* `import spacy`
* `from collections import defaultdict, Counter`
* `from bs4 import BeautifulSoup`
* `import requests`
* `import string` 
* `import math`               

<h3>License:</h3>
<p>This project and all resources abide under the MIT license in the root directory.</p>