# Water4Cities - Webinar #1
Water4Cities project - Webinar #1.

* data gathering infrastructure (adopted from Optimum project) for collecting Ljubljana aquifer groundwater data, weather data from darksky.net and Skiathos pumping data from legacy system Excel files
* API for data retrieval (also adopted from Optimum project) on the previously mention datasets
* data cleaning infrastructure (on Ljubljana aquifer data and present the results)
* data fusion infrastructure on a stream of smart-grid data
* simple and fast data-driven modelling capabilities on the top of W4C data gathering infrastructure with the usage of Python/scikit-learn/pandas.

[Slides](https://github.com/klemenkenda/w4c-webinar1/blob/master/slides.pdf)

## Software Requirements

* Anaconda (http://conda.io/docs/user-guide/install/index.html)
* Git (http://git-scm.com/downloads) (optional)

## Jupyter Libraries
The following code with python imports should work without errors in your Jupyter notebook.

```
import urllib.request
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn import linear_model
from sklearn.tree import DecisionTreeRegressor
from sklearn.svm import SVR
from sklearn.ensemble import RandomForestRegressor
from sklearn.model_selection import cross_val_predict
from sklearn.model_selection import cross_val_score
from sklearn import linear_model
from sklearn.ensemble import GradientBoostingRegressor
from sklearn.metrics import mean_squared_error
from sklearn.metrics import r2_score
```