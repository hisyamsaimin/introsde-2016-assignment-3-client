# introsde-2016-assignment-3
for submission of assignment 03

Student name: Muhamad Hisyam bin Saimin

Email: muhamad.binsaimin@studenti.unitn.it

For this assigment I worked with my best friend Chukwudi Uzoma https://github.com/ChukwudiUzoma

Used technologies: 
*SOAP
*Java
*XML
*JAX-WS
*Java Persistence API (JPA)

This repository contains only the Java client app. The stub classes were generated using wsimport.

The server project can be found in below link:
>> https://github.com/ChukwudiUzoma/introsde-2016-assignment-3-server

And the server is deployed @ https://enigmatic-chamber-18596.herokuapp.com/ws/people?wsdl

## Instruction on how to run the project:

The program uses ant build-tool for running. To execute the program, please download from thopen the terminal and run the following command in the root directory of the program:
	
ant execute.client
	
The above command installs all dependencies and executes the client. The client sends requests to the remote server running on Heroku and prints the results to the terminal and also saves them to logs in the root folder.
