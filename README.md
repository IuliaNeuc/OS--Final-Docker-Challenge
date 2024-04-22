# OS--Final-Docker-Challenge
# Challenge 3

Challenge 3 Journal

Date: 2024-04-19

Objective
Implement a full-stack application using Docker Compose, incorporating a database component.

Steps Taken

1 Folder Setup

Used the provided folder challenge3.
Added all files present in challenge3.zip to the challenge’s root folder.

![alt text](image-1.png)
 



2 Environment Configuration

Created the .env file with appropriate values for the configuration variables:
 
 ![alt text](image-2.png)

3 Docker Compose Setup

Created the docker-compose.yml file with configurations for three services:
•	nginx
•	node-service
•	db

 ![alt text](image-3.png)

4 Service Verification

Ensured all services were running properly:

First Step:

 
![alt text](image-4.png)


Second Step:

Checked using docker-compose ps.
Verified that all containers were up and running without any errors.

 ![alt text](image-5.png)

You can check the status of the containers by Docker app:

 ![alt text](image-6.png)
 
 ![alt text](image-7.png)


5 Application Testing

Accessed the endpoints:
http://localhost:8080/api/books
http://localhost:8080/api/books/1
Ensured that the expected JSON messages were returned.







6Expected Outcomes

Accessing http://localhost:8080/api/books should return a JSON message with all books:
 
![alt text](image-8.png)

Accessing http://localhost:8080/api/books/1 should return a JSON message with one book:

![alt text](image-9.png)
 
Executing docker-compose ps should show all services running properly.

Challenges Faced

•	The initial setup process was challenging due to insufficient instructions provided.
•	Spent several days researching and understanding database setup and environment variable configurations.
•	Lack of detailed guidance led to the need for independent research to gather required information.

Observations

Despite the initial challenges, the implementation process enhanced my understanding of Docker Compose and database integration.
Learned the importance of thorough documentation and clear instructions in technical tasks.

Conclusion

By overcoming initial hurdles and conducting independent research, the full-stack application was successfully implemented, demonstrating effective integration of web server, application, and database components using Docker Compose.
