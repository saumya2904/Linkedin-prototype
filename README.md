# LinkedIn-Prototype

1. A prototype of LinkedIn, a business and employment-oriented service with REST services using Node.js (Express), React.js and Redux.

2.	Designed and implemented distributed service-oriented framework for the application using Kafka.

3. Implemented connection pooling (with MongoDB and MySQL) for database access, used PassportJS with JWT for maintaining the user session. 

Application Architecture Diagram
![alt text](https://github.com/saumya2904/Linkedin-prototype/blob/master/Project%20Images/Architecture%20Diag.png)

Database Schema
![alt text](https://github.com/saumya2904/Linkedin-prototype/blob/master/Project%20Images/Database%20Schema.PNG)

Performace Graph ( JMeter Testing )
![alt text](https://github.com/saumya2904/Linkedin-prototype/blob/master/Project%20Images/Performance%20Graph.jpg)

# Features Provided
User Login and Sign Up
Recruiter Login and Sign Up
Search People
Search Jobs
Connect People / Recruiters
Easy Apply / Custom Apply
View Connections
Search Jobs based on Location, Company Name
Accept / Remove / Ignore Connections
Post Jobs
Specific To Recruiter
Send / Receive Messages
View Half Filled Forms (specific to recruiter)
Number of views of your post (specific to recruiter)
View Clicks on your post (specific to recruiter)
View Number of Applicants of your post (specific to recruiter)
View Your Top Posts (specific to recruiter)

# Technologies Used

React
Redux
Node
AWS RDS MySql
Mongo DB Cluster
Kafka
Json Web Token

# Installation Requirements
For development, you will only need Node.js installed on your environement. And please use the appropriate Editorconfig plugin for your Editor (not mandatory).

$ node --version
v0.10.24

$ npm --version
1.3.21

## Node installation on Linux
sudo apt-get install python-software-properties
sudo add-apt-repository ppa:chris-lea/node.js
sudo apt-get update
sudo apt-get install nodejs

## Node installation on Windows:
Install from official website of NodeJS.

## Front End
Install
$ git clone https://github.com/saumya2904/Linkedin-prototype.git
$ cd LinkedIn-prototype/linkedin/
$ npm install
$ npm start

## Back End
$ git clone https://github.com/saumya2904/Linkedin-prototype.git
$ cd LinkedIn-prototype/Linkedin-Backend/
$ npm install
$ node index.js

## Kafka Back End
$ git clone https://github.com/saumya2904/Linkedin-prototype.git
$ cd LinkedIn-prototype/Linkedin-Kafka-Backend/
$ npm install
$ npm start

