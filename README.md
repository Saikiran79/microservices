# Micro Services
1. When we deploy web based applications in one server and because of more number of requests, if the application is serving bit slow, either we change the application capacity or upgrade the RAM processor. This approach is not much better.
2. Generally, Developers will never have access to QA, UAT or Prod servers. 
3. In office, A deployment team is responsible to deploy the code into servers. 
4. The better approach to handle more load is implement load balancing conditions / algorithms. 
5. To achieve load balancing, Instead of directly exposing URL's to clients, We have an intermediate server which takes the    request from client and decides to which server the requests should be redirected. 
6. Instead of we buy and maintain the servers, We are taking the subscriptions from the cloud service providers. 
They provide both hardware and software services. 
   Ex: AWS, GCP, Microsoft Azure. 
7. If we develop only a single WAR/ EAR file containing all application modules to achieve load balancing, We need to invest a lot of money. This approach is called as Monolithic Design. 
8. To overcome to problem we prefer Microservices. Here, As part of every small program we will make it as a separate project. 
9. A Microservice project must be a single independent deployable component. 
10. Below are the advantages of Micro Services:
  i. Improved Fault Isolation.
  ii. Eliminate vendor or technology lock-in. 
  iii. Ease of understanding. 
  iv. Smaller and faster deployments. 
  v. Scalability. 
11. Spring Cloud provides set of tools to the developers to deploy the code in distributed systems. 
12. There are so many tools available as part of Spring cloud. Some of them are: 
  i. configuration management
 ii. Open Feign 
 iii. Spring Clous Zookeeper
 iv. Spring Cloud Net Flix etc
13. With introduction of Spring Cloud, We will never place configuration files in server. 
14. We will place all configuration files in GIT repository. 
15. Whenever there is a change in the passwords, We will update the passwords in GIT. 

