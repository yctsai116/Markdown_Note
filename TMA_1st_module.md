# TMA 1st module (8/13) 
#### Author: Yi-Chan Tsai
---
---
# Proposal 1 : Encapsulate the postman jason->jason API by Visualization web interface made in Python 

This work can improve the testing process in B03 testing.

## Challenge 

1.  jason to table\
    Huge amout of resources on the Internet. This can be done even with simple pandas funtion Pandas read_json(). Nested jason can also done with pd.json_normalize

reference: 
https://towardsdatascience.com/how-to-parse-json-data-with-python-pandas-f84fbd0b1025
http://json2table.com/
https://jsongrid.com/json-grid

2. Python build web\
   It can be done with Django
   reference: https://developer.mozilla.org/zh-TW/docs/Learn/Server-side/Django/Introduction

3. Python call Restful API\
   It can be done with python requests library
   reference: https://www.nylas.com/blog/use-python-requests-module-rest-apis/

## Might be useful 
1. Rendering Data-Frame to html template in table view using Django Framework https://www.geeksforgeeks.org/rendering-data-frame-to-html-template-in-table-view-using-django-framework/
2. Tutorial https://www.learncodewithmike.com/search/label/Django%E6%95%99%E5%AD%B8%E7%B3%BB%E5%88%97?updated-max=2020-03-11T22:28:00%2B08:00&max-results=20&start=14&by-date=false

## Worth trying
1. make directory
```
mkdir django4B03
cd django4B03
```

2. build a virtual environment
```
C:\Users\YOUR_NAME\django4B03> python -m venv django4B03_venv
```
3. active the virtual env.
```
C:\Users\YOUR_NAME\django4B03> django4B03_venv\Scripts\activate

```
4. what I should see
```
(django4B03_venv) C:\Users\YOUR_NAME\django4B03>
```
5. install Django1.8
```
(django4B03_venv) ~/django4B03$ pip install "django<1.9"

```
6. make sure install success
```
(django4B03_venv) ~/django4B03$ python

>>> import django
>>> django.VERSION
(1, 8, 6, 'final, 0')
```

reference: https://djangogirlstaipei.gitbooks.io/django-girls-taipei-tutorial/content/