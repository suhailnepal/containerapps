## Readme

This repo will have all the files for a simple feedback application written in Python - Flask, the plan here is to Dockerise the application. 

The following are the different components of the application: 

--> Feedback application: Written in Python flask, and will serve as a frontend for the user to provide feedback. 
--> Redis: To store in memory feedbacks when it's submitted on the feedback application. 
--> Worker: To update the Database from update from Redis, at this stage I m leaning towards Golang but either Python or Golang. 
--> db: To store all the feedback for the product
--> Dashboard application: Written in Python flask, with a simple dashboard on all the feedbacks submitted. 