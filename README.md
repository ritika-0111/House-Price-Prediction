# House-Price-Prediction
Model deployment with flask framework, using Linear Regression to predict the sales value in the third month using rate of interest and sales of the first two months.

Deploy Machine Learning Models Using Flask to take your models from jupyter notebook to production.

## env setup and Flask installaion
Create virtual env
```bash
py -m venv env
```

Activate virtual env  
```bash
env/Scripts/activate
```

Install Flask in your env
```bash
pip install flask
```

```bash
set FLASK_APP = app.py
```

## Dataset
Created dummy sales dataset for this project which has four columns — rate of interest, sales in first month, sales in second month and sales in third month.  

## Project Structure
model.py                 (contains code for the machine learning model to predict sales in the third month based on the sales in the first two months.)  
app.py                   (contains Flask APIs that receives sales details through GUI or API calls, computes the predicted value based on our model and returns it.)  
request.py               (uses requests module to call APIs defined in app.py and displays the returned value.)  
  
