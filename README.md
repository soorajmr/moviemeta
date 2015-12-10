<h1 align=center>Moviemeta</h1>

<p align=center>Harvard Data Science course CS-109 project repository, created by Mark Reinke, Wonsun Kim and Sooraj Raveendran </p>

<hr>



## Project Summary

Video delivery is gradually getting liberated from the traditional satellite and cable infrastructure. Also, the barriers of entry for video production and distribution is dropping significantly. As the landscape changes and the [new entrants want to achieve scale] (http://www.nytimes.com/2015/10/19/technology/netflix-faces-challengers-in-its-push-to-expand-globally.html?_r=0), understanding local sensitivities become very important. 

The high level idea of our project is to apply text mining techniques on movie mata data like plot summaries to gain non-obvious insights to the content of the movies. This analysis is carried out across different dimensions to study cultural, geographical and temporal patterns in the contents of movies.

## Links

- For more details on the approaches we use, please see the [process notebook] (https://github.com/soorajmr/moviemeta/blob/master/notebooks/process_book.ipynb) 
- For a general overview of the results, see http://markreinke.github.io/moviemeta_web/

## Contents of the repository

- The notebooks directory has all the Jupyter notebooks that implement data cleaning and various analyses using LDA, Doc2Vec, etc. For an index, see the [process notebook] (https://github.com/soorajmr/moviemeta/blob/master/notebooks/process_book.ipynb) 
- The resources directory contains references and other information.
  - [Initial questions that drove the analyses] (resources/Questions.md)
  - [Technical backgroud - Resources] (resources/Resources.md)
  - [Data sources we explored] (resources/Datasources.md)

## Python packages

Anaconda Python distribution with additional packages:

- [Gensim](https://radimrehurek.com/gensim/)
- [TextBlob](https://textblob.readthedocs.org/en/dev/)
- [Slugify](https://github.com/un33k/python-slugify)
- [Rake](https://pypi.python.org/pypi/python-rake/1.0.5)
- [pyLDAvis](http://pyldavis.readthedocs.org/en/latest/)

## Data

Please download the data from our [dropbox](https://www.dropbox.com/sh/bhrp12eqlj3zw0f/AAAlf4VJED2JXHLL6yUzuWoea?dl=0) and change the dropbox directory at the beginning of all notebooks to your local dropbox folder