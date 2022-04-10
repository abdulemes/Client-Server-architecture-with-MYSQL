# Project Workflow

## Setting up VM Environment 

Step 1 - Creating 2 linux ubuntu EC2 instances.

![IMG_9661](https://user-images.githubusercontent.com/93732510/162610450-fb3dd66a-c402-4c10-b56c-03b8a30f3f7f.jpg)

## Configuring mysql server

Step 1 - logging in to the server instance.

![IMG_9662](https://user-images.githubusercontent.com/93732510/162610657-b14a3dc8-deb4-47a2-89ec-e436e9250cef.jpg)

Step 2 - The apt package manager is updated and then mysql server installed.

![IMG_9663](https://user-images.githubusercontent.com/93732510/162610715-87dd733d-67d0-4b5a-a06d-0aa4171faa7d.jpg)

![IMG_9665](https://user-images.githubusercontent.com/93732510/162610734-e0a3b2d8-2d5a-40ad-a867-a76c585ee037.jpg)

Step 3 - The server is then started, enabled and status checked.

![IMG_9666](https://user-images.githubusercontent.com/93732510/162610889-198a151e-e46e-45d6-99e2-e0c97d81874c.jpg)

## Configuring mysql client

Step 1 - logging in to the server instance.

![IMG_9668](https://user-images.githubusercontent.com/93732510/162611055-7921dd8c-022e-4549-9d17-478b8505fca0.jpg)

Step 2 - The apt package manager is updated and then mysql client installed.

![IMG_9669](https://user-images.githubusercontent.com/93732510/162611115-24731403-3ae8-4091-ac4e-ba4116fcaf2a.jpg)

![IMG_9670](https://user-images.githubusercontent.com/93732510/162611135-4f9e2766-e8d1-4bda-9503-2f2866299b92.jpg)

## Setting up Database
Step 1 - Security group for mysql server is configured to allow traffic from client's local IP.

![IMG_9676](https://user-images.githubusercontent.com/93732510/162611277-821753be-6029-4490-aee9-83862871a2fb.jpg)

Step 2 - In the mysql server, mysql secure installation is first of all done.

![IMG_9677](https://user-images.githubusercontent.com/93732510/162611425-c6e36b90-2219-471d-96a6-bef2466da72e.jpg)

Step 3 -  Logging in to the mysql using sudo privilege.

![IMG_9678](https://user-images.githubusercontent.com/93732510/162611507-ad39e516-2be0-4b0e-bd87-18b3ad8721e4.jpg)

Step 4 - A user, database are created and permissions set.

![IMG_9680](https://user-images.githubusercontent.com/93732510/162611583-86ce179d-366a-45c9-92d7-a983c3446729.jpg)

Step 5 - Mysql configuration file is updated to allow internal connection from remote hosts.

![IMG_9683](https://user-images.githubusercontent.com/93732510/162611709-1837c111-1e44-45e1-989a-6f01f5a1a469.jpg)

Step 6 - Now the mysql server is connected from the client server using the user credentials that was previously created.

![IMG_9684](https://user-images.githubusercontent.com/93732510/162611780-9add3fa0-1f58-4e23-97ac-3489baba41b6.jpg)

Step 7 - Query commands are checked to see that the user can perform with assigned privelege.

![IMG_9685](https://user-images.githubusercontent.com/93732510/162611850-354d0e27-f94a-4195-bce7-b14a83504e20.jpg)

