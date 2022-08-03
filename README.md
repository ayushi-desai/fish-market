# Fish Dataset
<br/>

**Introduction**
<br/>
The repo aims to perform analysis on the given fish market dataset. The analysis involves performing a Random forest as a classification algorithm on the dataset.
<br/>
<br/>
**Web Application**
<br/>
In order to showcase the classification, a web application has been built on Heroku servers. The interactive model estimates a target fish weight based on user inputs on a specific fish's vertical, diagonal, horizontal, and height measurements.
<br/>
<br/>
**Dataset**
<br/>
The dataset consists of seven characteristics including five length measurements, fish species, weight, and numerical and categorical data. The dataset was produced by Aung Pyae and is available on the kaggle.com website. Given that there is a significant association between fish length and fish weight, the dataset is ideal for regression modelling. The "Weight" feature is utilised as the target feature in a linear regression analysis.
Dataset can be downloaded from: https://www.kaggle.com/aungpyaeap/fish-market
<br/>
<br/>
**Features**
<br/>
- Species (str): The type of fish
- Weight (int): The recorded Weight of the fish in grams (g)
- Length1 (int): Vertical length in centimeters (cm)
- Length2 (int): Diagonal length in centimeters (cm)
- Length3 (int): Cross length in centimeters (cm)
- Height (int): Height in centimeters (cm)
- Width (int): Diagonal width in centimeters (cm)
<br/>

**Demo**
<br/>
You can check the demo here: https://fish-deploy.herokuapp.com
<br/>
