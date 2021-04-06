# kNN-based Recommender Engine
![enter image description here](https://cdn.lynda.com/course/5028662/5028662-637491087568455386-16x9.jpg)

A recommender system, or a recommendation system, is a subclass of information filtering system that seeks to predict the "rating" or "preference" a user would give to an item. It is widely used to make recommendations based on a user's past behaviours and preferences. Recommender systems are often based on the kNN (k-nearest neighbor) algorithm, which makes recommendations based on shared similar features. It can be used to solve both classification and regression problems.


# Project Description
The objective of this project is to build a kNN-based recommender system in order to predict the top 5 movie based on a given movie, in this case "The Post". As there is no need for classification or regression, the nearestNeighbors model and neighrbors() method are used to find the 5 most closely related films. This project does not include model performance testing due to the small size of the dataset.


## Steps

 1. Data Exploration
 2. Building a kNN-based Recommender System
 3. Getting Recommendations

## Requirements

**Python.** Python is an interpreted, high-level and general-purpose programming language. 

**Integrated Development Environment (IDE).** Any IDE that can be used to view, edit, and run Python code, such as:
- [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb#recent=true)
- [Jupyter Notebook](https://jupyter.org/).

### Packages 

Install the following packages in Python prior to running the code.
```python
import pandas as pd
import numpy as np
from sklearn.neighbors import NearestNeighbors
```

## Launch
Download the Python File *CA06_kNN_based_Recommender_Engine* and open it in the IDE. 

## Authors

[Silvia Ji](https://www.linkedin.com/in/silviaji/) - [GitHub](github.com/jisilvia)

## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.

## Acknowledgements

The project template and dataset provided by [Arin Brahma](https://github.com/ArinB) at Loyola Marymount University.
