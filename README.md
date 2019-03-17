# LinkedIn-Prototype

1. A prototype of LinkedIn, a business and employment-oriented service with REST services using Node.js (Express), React.js and Redux.

2.	Designed and implemented distributed service-oriented framework for the application using Kafka.

3. Implemented connection pooling (with MongoDB and MySQL) for database access, used PassportJS with JWT for maintaining the user session. 

## Application Architecture Diagram
![alt text](https://github.com/saumya2904/Linkedin-prototype/blob/master/Project%20Images/Architecture%20Diag.png)

## Database Schema
![alt text](https://github.com/saumya2904/Linkedin-prototype/blob/master/Project%20Images/Database%20Schema.PNG)

## Performace Graph ( JMeter Testing )
![alt text](https://github.com/saumya2904/Linkedin-prototype/blob/master/Project%20Images/Performance%20Graph.jpg)

# Features Provided
1. User Login and Sign Up
2. Recruiter Login and Sign Up
3. Search People
4. Search Jobs
5. Connect People / Recruiters
6. Easy Apply / Custom Apply
7. View Connections
8. Search Jobs based on Location, Company Name
9. Accept / Remove / Ignore Connections
10. Post Jobs
11. Specific To Recruiter
12. Send / Receive Messages
13. View Half Filled Forms (specific to recruiter)
14. Number of views of your post (specific to recruiter)
15. View Clicks on your post (specific to recruiter)
16. View Number of Applicants of your post (specific to recruiter)
17. View Your Top Posts (specific to recruiter)

# Technologies Used

1. React
2. Redux
3. Node
4. AWS RDS MySql
5. Mongo DB Cluster
6. Kafka
7. Json Web Token

# Installation Requirements
For development, you will only need Node.js installed on your environement. And please use the appropriate Editorconfig plugin for your Editor (not mandatory).

$ node --version
v0.10.24

$ npm --version
1.3.21

## Node installation on Linux
1. sudo apt-get install python-software-properties
2. sudo add-apt-repository ppa:chris-lea/node.js
3. sudo apt-get update
4. sudo apt-get install nodejs

## Node installation on Windows:
Install from official website of NodeJS.

## Front End
1. $ git clone https://github.com/saumya2904/Linkedin-prototype.git
2. $ cd LinkedIn-prototype/linkedin/
3. $ npm install
4. $ npm start

## Back End
1. $ git clone https://github.com/saumya2904/Linkedin-prototype.git
2. $ cd LinkedIn-prototype/Linkedin-Backend/
3. $ npm install
4. $ node index.js

## Kafka Back End
1. $ git clone https://github.com/saumya2904/Linkedin-prototype.git
2. $ cd LinkedIn-prototype/Linkedin-Kafka-Backend/
3. $ npm install
4. $ npm start

