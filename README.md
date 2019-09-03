
         What is open banking ?
                  Open Banking is a secured technology (APIs) that allows the consumer or an SME (Small and Medium-sized Enterprises) to safely share their transaction data with and authorized third party.
         It also enables consumer/SMEs to instruct that that third party to send a payment from their accounts if they want to.
         
         The data that the bank holds on the consumer belongs to the consumer and not to the financial instutuions.
         Open Banking applies to Saving Ac, Current Ac, creditCards , E-wallets , Prepaids.
         Ex: Amazon wallet, Uber wallet....


Imran Gulamhuseinwala: Why Open Banking is the Future of Fintech : https://www.youtube.com/watch?v=aywk5qqTRWw


 


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











maven build skip error module build using option --fail-at-end:
         https://maven.apache.org/guides/mini/guide-multiple-modules.html
         
         
maven verify version and java path : 
mvn -version
in bash terminal : $ export JAVA_HOME='/c/' 


         
mvn clean install --fail-at-end -Dmaven.test.skip=true


Update local branch to stable release :
git fetch --all --tags --prune
git checkout tags/<tag_name> -b <branch_name>

Ex: $ git checkout tags/v2.6.0


WSO2 ESB / EI for Begineers
https://www.youtube.com/watch?v=27fpZDLonzw&list=PLxoOrmZMsAWzG_TkytzDKPKzJrPXnYAMY


Invoking APIs using a Web App Deployed in WSO2 AS : samples/PizzaShack/pizza-shack-web
     https://docs.wso2.com/display/AM140/Invoking+APIs+using+a+Web+App+Deployed+in+WSO2+AS







---------------------------------------------------------------
<br><br>

Maven build error at module : wso2ApiManager/git/product-apim/modules/p2-profile/product

Application failed, log file location: /root/.m2/repository/org/eclipse/tycho/tycho-p2-runtime/0.13.0/eclipse/configuration/1567501707194.log

[INFO] ------------------------------------------------------------------------
[INFO] BUILD FAILURE
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  07:27 min
[INFO] Finished at: 2019-09-03T09:08:31Z
[INFO] ------------------------------------------------------------------------
[ERROR] Failed to execute goal org.wso2.maven:carbon-p2-plugin:1.5.4:materialize-product (creating-gateway-worker-profile) on project am-p2-profile: Cannot generate P2 metadata: P2 publisher return code was 13 -> [Help 1]
[ERROR]
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR]
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoExecutionException


-----------------------------------------------------------------

-----------------------------------------------------------------




