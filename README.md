Using Maven to Build WSO2 Products

https://wso2.github.io/using-maven.html

WSO2 GitHub Repositories:
https://wso2.github.io/github-repositories.html

Overview of the WSO2 repositories
The WSO2 source code is organized into separate repositories in GitHub, and each WSO2 product is built using several of these repositories. Therefore, if you are interested in editing the source code, you need to first identify the repositories that you require. For the complete list of repositories used by WSO2 products, see the sections below. If you are still not sure which repositories you need, send an email to dev@wso2.org.

There are two types of WSO2 repositories:

Component-level repositories: A component repository consists of the source code relevant to a particular component. Each WSO2 product release is built using combinations of these component repositories. Therefore, if you want to do modifications to a particular function in a product, you need to clone the Git repositories relevant to that function. If you want to know more about component repositories and the tags used for a product release, send an email to dev@wso2.org.

Product-level repository: A product repository consists of the build scripts and profiles that are used for building the product. It also includes the integration test cases. For example, given below is the product repository for the WSO2 Identity Server 5.1.0 release. When you build this product repository, all the component repositories that are required for the IS 5.1.0 release will be automatically fetched from Nexus. Therefore, you can simply clone this repository tag to your computer and build it to get a standard product pack.





Working with the Source Code:
https://docs.wso2.com/display/AM200/Working+with+the+Source+Code

Installing and Configuring the Databases : https://docs.wso2.com/display/AM210/Installing+and+Configuring+the+Databases
Changing the Default API-M Databases : https://docs.wso2.com/display/AM260/Changing+the+Default+API-M+Databases
Tutorials : https://docs.wso2.com/display/ESB500/Tutorials


WSO2 API Manager Developer Fundamentals :
https://wso2.com/training/api-manager-developer-fundamentals


WSO2 ESB / EI for Begineers
https://www.youtube.com/watch?v=27fpZDLonzw&list=PLxoOrmZMsAWzG_TkytzDKPKzJrPXnYAMY


Invoking APIs using a Web App Deployed in WSO2 AS : samples/PizzaShack/pizza-shack-web
     https://docs.wso2.com/display/AM140/Invoking+APIs+using+a+Web+App+Deployed+in+WSO2+AS


