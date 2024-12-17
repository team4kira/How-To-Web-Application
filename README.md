# How-To-Web-Application
How to Setup a Web Application using GitHub and Azure

How To: 

Steps in GitHub
1.	Create a repository can be private or public (note down the name, as this will be used in the Azure step afterwards)
2.	Upload Files:
3.	The files you are uploading should contain your index.html and any CSS and images being utilized for the site.
4.	Ensure that the site is working in live view of Virtual Studio Code, if it is functional, you should upload it to the GitHub repository. 

Steps in Azure: 
1.	Go to Static Web Apps followed by Create Static Web App 
2.	Create (Enter the Following After)
  -	Subscription (should auto populate, unless you have more than one)
  -	Resource Group (if you don’t have one you can create a new one) 
  - Name (for organizational purposes) 
  -	Plan (there is a free option for those doing this as a hobby. This entitles you to two free Web Applications)
  -	Region for Azure environment - choose a region near your geographical location
3.	In this same page under Deployment Details select GitHub and Login with GitHub (Enter the Following)
  - Organization (GitHub account name) 
  -	Repository – make sure it is the same repository you uploaded your web application files to. 
  -	Branch – main 
4.	Tags – optional 
5.	Create 
6.	After it propagates you should be given an auto-generated name like something-random.azurestaticapp.net. If you don’t like the auto-generated name, you can use sites like GoDaddy to change the domain name for a nominal fee
