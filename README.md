# my-employee-portal

#How to run backend code

a) import employee-registration-portal into Eclipise IDE (using Spring boot)  
b) right click on project  
c) run as --> Java Application  
d) select RegistrationApplication as main class  

it will deploye the below API into inbuild tomcat server  
 # GET API-  http://localhost:8081/portal/registration/employees  (display list of employees based on first name)  
 # POST API - http://localhost:8081/portal/registration/register (register the employee details)  
  PAYLAOD Example - {"firstName":"Ram","lastName":"gopal","gender":"MALE","dob":"12-10-1991","department":"IT"}  
			  
#Now our backend is ready to test  

#How to run frontend code  
I am using angular5 for development and bootstrap and HTML5  
import the project into any IDE (VCS or InteliJ)  
 #run below npm commands  
 a) npm install (it will download all the dependencies)  
 b) npm start (to start the local server)  
 c) go to http://localhost:4200/ (it will open the my-employee-portal page )  
 d) Enter all details and register  
 e) you can display the registered employees  
