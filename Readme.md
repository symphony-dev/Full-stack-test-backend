<h3> AWS-EC2-Backend-Frontend-Service-Deployment </h3>

Repository Name: Full-stack-test-backend.git
Repository URL: https://github.com/symphony-dev/Full-Stack-test-backend.git

Repository Name: Full-stack-test-frontend.git
Repository URL: https://github.com/symphony-dev/Full-Stack-test-frontend.git

<h3> Steps for Deployment </h3>

1 - Create and launch a new Ubuntu Server on AWS EC2 for backend service 

2 - Create and launch a new Ubuntu Server on AWS EC2 for frontend service

3 - Connect to Ubuntu EC2 Instance via SSH for backend 

4 - Install node, npm, mysql, Apache, git services on the server and start services 

5 - Clone git repo

6 - Start the API by running node server.js which will show web server at port 5000 is running.

7 - Connect to Ubuntu EC2 Instance via SSH for frontend

8 - install npm service

9 - Update index.js file to connect to backend API and configure the path to API by changing apiURL in config.js 

10 - Build the frontend app with npm run dev


<h3> AWS Base Url </h3>
http://ec2-18-216-107-145.us-east-2.compute.amazonaws.com:5000/api/
                             OR
http://18.216.107.145:5000/api/

Base Url: http://localhost:5000

<h3> Live Demo(AWS) </h3>
http://ec2-3-21-237-106.us-east-2.compute.amazonaws.com:9527
