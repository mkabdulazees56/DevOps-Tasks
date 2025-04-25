Deploying frontend on S3, backend on EC2 and configuring database of RDS
------------------------------------------------------------------------
This setup is a full-stack web application deployment on AWS, where:

Frontend (React) is hosted on S3 as a static website.

Backend (Node.js + Express) is deployed on EC2.

Database (MySQL) is hosted on RDS.

Communication happens over the internet between the frontend (S3), backend (EC2), and database (RDS).

🎯 Goal:
To deploy a full-stack React + Node.js + MySQL application using Amazon Web Services (AWS).

🧱 Components & Hosting Services:

Component	Hosting Service	Purpose
Frontend	  Amazon S3	       Host static React website
Backend	    EC2 Instance	   Run Node.js/Express API
Database	  Amazon RDS	     Manage MySQL database

