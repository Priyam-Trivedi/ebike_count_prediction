
# Rental Bike Share Prediction 🚴

Bike sharing systems are a new generation of traditional bike rentals where the whole
process from membership, rental and return back has become automatic. Through
these systems, users are able to easily rent a bike from a particular position and return
back at another position. Currently, there are about over 500 bike-sharing programs
around the world which is composed of over 500 thousand bicycles. Today, there exists
great interest in these systems due to their important role in traffic, environmental and
health issues. Apart from interesting real-world applications of bike sharing systems, the
characteristics of data being generated by these systems make them attractive for the
research.
The goal here is to build an end-to-end regression task. Here the user will provide the
data and the result will be given by the best performing hyper tuned Machine Learning
model

## Table Content ✏️

 - Demo
 - Overview
 - Dataset
 - Installation
 - Deployment
 - Deployment
 - Documentation
 - Directory Tree
 - Technology Used
 - Bug/Feature Request
 - Future scope of project
 





## Demo ✔️
Heroku:- https://ebikecountpred.herokuapp.com/


AWS(Ec2):- https://ec2-54-84-85-146.compute-1.amazonaws.com:5000 [opens on sunday only]

![bike rent](https://i.imgur.com/xYGFeks.gifhttps://i.imgur.com/xYGFeks.gif)


  
## Overview 📜

This is a Flask web app which predicts the count of the bikes available based on the user's input in which there are several categories to fill in like the season,windspeed,humidity,temperature,at what time user is searching and other things by which model will predict the number of bikes will be available for that particular input and conditions.Data which user enters will be stored in MongoDB for the future use,logging is done at every step.
AIM:
Taking climatic conditions into consideration this model will predict the number of bikes can be used in the particular hour of a day.The bike company make sure that those number of bikes should be available at that time in order to get the optimum utilization of those bikes and earn maximum profits.

  
## DataSet 📊

To Know more about data and its characterstics you can download dataset form https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset 



  
## Installation 🗄️

The Code is written in Python 3.8 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://github.com/Priyam-Trivedi/ebike_count_prediction/tree/master) the repository:
```bash
pip install -r requirements.txt
```

## Deployement
### Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

### AWS(Amazon Web Services)
Login or signup with free tier in order to create virtual amchine(EC2 instance) for free. 
Note:- In free trier virtual Machine will only give free service for 720hr almost a month after that you will be charged , so use carefully. I usally stop instance when it is not needed to avoid extra charge. so it may happen that deployment link for AWS might not work  
[![](https://i.imgur.com/r9pJG6J.png)](https://heroku.com)

Our next step would be to follow the instruction given on [AWS EC2 Instance Documentation](https://aws.amazon.com/getting-started/tutorials/deploy-code-vm/) to deploy a web app.


## DataBase

![App Screenshot](https://i.imgur.com/JMI7vmQ.png)

  
## Directory Tree

```javascript
├── static 
│   ├── styles
│   |   ├── css
│   |   ├── forms
│   |   ├── img
│   |   ├── js
│   |   ├── vendor
├── template
│   ├── index.html
│   ├── result.html
│   ├── 500.html
│   ├── 404_error.html
│   ├── error.html
├── Procfile
├── bike sharing.ipynb
├── day.csv
├── hour.csv
├── README.md
├── main.py
├── DT_bike_sharing.pkl
├── requirements.txt


```

  
## Documentation

[Documentation](https://linktodocumentation)

[Documentation](https://linktodocumentation)

[Documentation](https://linktodocumentation)



  
## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/3/32/Mongo-db-logo.png" width=280>](https://account.mongodb.com/account/login?n=%2Fv2%2F613a4456b613903d19ff6a0d&nextHash=%23metrics%2FreplicaSet%2F613a452891e112710853bd33%2Fexplorer%2Fbike%2Fuser_details%2Ffind)[<img target="_blank" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSEHMPPej34qcJENKeCNdpqnZ5V9vLrmwVIvw&usqp=CAU" width=280>](https://aws.amazon.com/) [<img target="_blank" src="https://seeklogo.com/images/B/bootstrap-logo-69A1CCC10B-seeklogo.com.png" width=200>](https://getbootstrap.com/) 


## Bug/Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue](https://github.com/Priyam-Trivedi/ebike_count_prediction/issues) here by including your search query and the expected result

  
## Contributors <img src="https://raw.githubusercontent.com/TheDudeThatCode/TheDudeThatCode/master/Assets/Developer.gif" width=35 height=25>

- [Priyam Trivedi](https://github.com/Priyam-Trivedi)
- [Sravanthi Shoroff](https://github.com/sravanthishoroff)

## Future Scope

* Use multiple Algorithms
* Optimize Flask app.py
* Front-End 
