Complaint Redressal System..
Description
ABC Telecom Ltd. is one of India’s major telecommunication service providers offering landline, mobile phone and Fiber optic broadband services across the country. Their customer services group is interested in providing a set of customer redressal services through the development of a new application using the state-of-art technologies such as Spring-boot for the development of java-based services, and UI using Angular and integrate them suitably, so that all the necessary services are taken care of through this application. They want to have an online complaint management system where the customers can raise complaints regarding their landlines and broadband services.
Scope:
The system should be a web-based application, developed using spring framework as a backend and angular as a front-end that performs the following functions:
1.Enables the Administrator to create and manages the lifecycle of different types of users
Customer
Manager
Engineer
     2. Enables the customers to login to the portal to raise and track complaints related to the services availed by them
     3. Enables the manager to login, view the complaints raised by the customers and assign the ticket to the engineers based on the PIN Code
     4. Enables the engineers to pick up the tickets, work on them, enter the status of the task. They can also re-assign it to the Field Workers if they cannot resolve it from the data center.
 
Recommended Tools:
Junit to perform Unit Testing
Spring boot for web application
MySQL Database for storing all the data and appropriate JDBC driver for connectivity
Angular for Front End for all UIs.
DevOps and production technologies: Git, GitHub, Docker
 
Requirements
1.Admin user is the super user of the system. The admin user creates other categories of user like customer, manager, and engineers. The admin user has the privilege to create, update and delete the records through the web interface and can access the entire system.
2.Customer users can perform tasks like creating a complaint, view complaints, tracking the complaint and providing feedback on the resolution of the complaint through the web UI. The feedback provision is an optional feature. Customers should provide the following minimal details such as name, address (with PIN Code), telephone / mobile number, type of problem (cannot make a call, but receive a call or can make calls, but cannot receive calls, or neither make nor receive calls). Once successfully submit the complaint, a ticket is raised and shared it with the customer. At that time, the status of the ticket will be ‘RAISED’
3.Managers can pick the tickets from the active ticket list and assign them to the engineers based on the PIN code of the customer (where the service is installed). There should be different managers to take care of different PIN codes. You are expected to use at least about 5 – 10 different PIN codes, and there should be as many managers for assignment. Managers should also be able to see the status of all the tickets in all the areas.
4.Engineers can log in and view all the tickets assigned to him/her and can pick the tickets assigned to them and assign it the status of ‘WIP”, (work on the case, which is dependent on the type of problem and resolve) and update the status as ‘RESOLVED’. In case they are not able to resolve the issue at their end, they can remark that this needs to be reassigned to Field Workers in case of a cable fault or at the customers’ site, and flag it as ‘ESCALATED”
5.All the activities of all the use cases should be appropriately bound by session or other alternatives. Appropriate time-out to be provided for each user.
 
