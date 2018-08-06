# Classroom Occupancy Project -- *The Next Frontier!*

I originally began working on this project in the spring of 2017 as a student
in Georgetown University's Data Science Certificate Program. I worked
with four fellow students on our Capstone project, which created a web
application that incorporated supervised machine learning models to predict a
room's occupancy level based on real-time sensor data.

Our team began by collecting sensor data using a Raspberry Pi 3, while other
devices, such as a camera and motion sensor, were added later as we
experimented with potential new features to improve the model. My work on the
project primarily focused on cleaning the data and building the machine
learning models. The final structure of our dataset allowed me to build both
supervised regression and classification models; however, classification models
consistently proved superior in their ability to generalize on unseen data. 

Our team presented our final project at the completion of the program on July
1, 2017. Since over a year has passed since working on the project, I
decided that I wanted to look at it again with fresh eyes. The Georgetown
Data Science Certificate is an intensive semester long program, so time was always
a limiting factor. However, now that I've gained more experience over past
year building supervised and unsupervised models, I'd like start from scratch
and see where the data leads me!

To start fresh, I've only added the original datasets that we collected to this
repository. However, all of the original notebooks, visualizations and
models are still available in the [Georgetown University
repo](https://github.com/georgetown-analytics/classroom-occupancy) we created
for the project. 

### Data Set Description 
Number of Instances: 46,275  
Number of Attributes: 11  
Data Set Characteristics: Multivariate, Time-Series  
Attribute Characteristics: Real, Category  
Dates Collected: 3/25/2017, 4/1/2017, 4/8/2017, 4/22/2017, 4/29/2017, 5/5/2017,
5/6/2017, 5/12/2017, 5/13/2017, 6/1/2017, 6/10/2017

#### Attribute Information
date time year-month-day hour:minute:second  
Temperature, °Celsius  
Humidity, %  
CO₂, parts per million (ppm)  
Light, Lux  
Sound, Hz  
Door Status, open or closed  
Bluetooth, number of devices  
Non-Personal Bluetooth, number of devices  
Images, % of hist change  
Occupancy Count, number of students

#### Students on the original project
- Nikolay Bandura
- Abraham Montilla
- Mengdi Yue
- Svetlana Zolotareva
