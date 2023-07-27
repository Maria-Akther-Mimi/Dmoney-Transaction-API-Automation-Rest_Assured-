# Dmoney-Trnx-API-Automation-Rest_Assured

### An [API](https://api.postman.com/collections/1844288-143eb923-423f-4c91-a198-fe6e56d20e35?access_key=PMAT-01GJ3CC22Q0066PJWP3T0XHQ8G) is tested by using REST Assured framework.<br><br>

Here the following tasks are done:
1. Do Login by admin
2. Create 2 new customers and a agent
3. Give 2000 tk from System account to the newly created agent
4. Deposit 1500 tk to a customer from the agent account
5. Withdraw 500 tk by the customer to the agent
6. Send money 500 tk to another customer
7. Payment 100 tk to a merchant (01686606905) by the recipient customer
8. Check balance of the recipient customer<br><br>

### Technology: </br>
- IDE: Intellij
- Build tool: Gradle
- Language: Java <br>


## Framework used: <br>
- Rest Assured
- TestNG

### Prerequisites</br>
- Install jdk 11 or any LTS versio
- Configure JAVA_HOME and GRADLE_HOME
- Download Allure 2.23.0 and configure environment path
- Stable internet connection

### Project Run
- Clone the project from this repository [Dmoney-Transaction-API-Automation-Rest_Assured](https://github.com/Maria-Akther-Mimi/Dmoney-Transaction-API-Automation-Rest_Assured/edit/main/README.md)
- Open cmd in the root folder.
  
#### Run the Automation Script by the following command:
 ```
 gradle clean test 
 ```
 
 - Give the following commands by opening terminal in the project folder to create Allure Report:
```
allure generate allure-results --clean -o allure-report
 ```
 ```
 allure serve allure-results
```


## Rest Assured API Automation Allure Report 


![1](https://user-images.githubusercontent.com/58990500/204823153-6c01bcb5-f097-4f6e-9cf2-02a494bcbec0.PNG)



![2](https://user-images.githubusercontent.com/58990500/204823205-8113d907-fbc4-4bc3-9aeb-9900349729ef.PNG)



![3](https://user-images.githubusercontent.com/58990500/204823251-7d14f744-b2ce-4056-a660-c2c8bf03bbcd.PNG)
