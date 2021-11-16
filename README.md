

# 🏘️ Housing in France 2020

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](http://forthebadge.com)



Python project about sales related to buildings in France during 2020

In this project, we tried to understand what were the tendencies regarding real estate in France for the year 2020. 
We will also compare it with 2019 datas.

## Installation
<br/>


To download the dataset, click on this [link](https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres/).

For this project we will use the following libraries :
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from matplotlib import pyplot
import matplotlib
from collections import Counter
import plotly.express as px
import seaborn as sns
import squarify
import circlify
import folium
import json
```
Use the package manager [pip](https://pip.pypa.io/en/stable/) if you don't have them.

##  Preprocessing
<br/>

In the first part of the notebook, we will transform the raw data into a valuable dataset easier to plot and use for interpretations. We notably get rid of nan values, inconsistencies, or redundancy using simple Python functions. We only want to keep the interesting data we can use. We will also create new columns which we will take a look at after.
<br/>
## Analysis of the 2020 data

We mainly use pyplot, pandas, seaborn, squarify, circlify to make our interpretations out of our dataset.

We will first have a global vision of our dataset by looking at the proportion of the transactions' types, where do the transactions take place, the mean value of the transactions depending on their types, or the kinds of lands that are bought.

<br/>
<br/>

<p align="left"> 
  <img src=https://user-images.githubusercontent.com/63778269/136857595-36804b4a-a07a-44b8-ad9d-f8e0ba44b1b2.PNG width=450/> 
  <img src=https://user-images.githubusercontent.com/63778269/136857612-f73c88e5-b34d-4366-972c-f49ad5bef6cc.PNG width=350/>
</p>


Then we will focus on the difference between the departments in France. Take a look at the number, mean price, and m² price of each department and compare them to each other. For that we created interactive maps, using the folium library, of France to make our analysis easier to understand for everyone.

<br/>
<p align="left"> 
  <img src=https://user-images.githubusercontent.com/63778269/136858120-fd168bf6-6602-461c-9a1c-53fb469d7304.PNG width=430/>
  <img src=https://user-images.githubusercontent.com/63778269/136858138-6a81db9a-24f0-4a0a-b35c-4383fc926b8f.PNG width=375/>
</p>
<img src=https://user-images.githubusercontent.com/63778269/136858148-01faef81-aeac-4745-be45-8604f9b8f555.PNG width=/>
<img src=https://user-images.githubusercontent.com/63778269/136858125-bae5a1ce-56a4-4a5e-ad70-1fea196b5b80.PNG width=350/>
 <br/>
To finish we will zoom on the departments and analyze the difference between the cities. We will pay attention to the most attractive ones and have a special look at Paris, the capital of France, because it is the largest city in France and the center of French economy, politics, traffic and culture.

<br/>

<p align="center"> 
  <img src=https://user-images.githubusercontent.com/63778269/136859020-20a9096a-6ebf-4230-b40e-2d7c8cae7781.PNG width=400/>
  <img src=https://user-images.githubusercontent.com/63778269/136859026-22d6fd29-c4c4-4160-af49-0c072810bedc.PNG width=400/>
</p>
<p align="center"> 
  <img src = https://user-images.githubusercontent.com/63778269/136859027-6c60d176-3425-4585-b4fb-61dfc3a867f6.PNG width =600/>
</p>
<br/>


## Comparison between the 2020 and 2019 sales

To measure the impact of the sanitary crisis, we decided to compare the results between multiple years. 

<img src = https://user-images.githubusercontent.com/63778269/136859218-73229424-8153-40f5-8f44-a9f046f3a18a.PNG width=400/>

It was also a good way to see in which cities the french show interest with this animation.

<img src = https://user-images.githubusercontent.com/63778269/136859244-3c0d9c83-307f-4e9b-8af1-1d18dd3a50c8.gif width=400/>


## Conclusion

To conclude, we learned a lot from this project whether it is about Python or the real estate market and how it was affected by the COVID-19.


## Note

The notebook is in French but do not hesitate to contact me if you want more details in English.

### Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

# 🧍‍♂️ Authors

* **Hugo Debes** _alias_ [@hugodebes](https://github.com/hugodebes)
* **Aurelien Delicourt**
* **Charles Delemazure** _alias_ [@Charlesdele](https://github.com/Charlesdele) 


