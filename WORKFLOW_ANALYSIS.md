## What triggers this workflow to run? 
When the code is pushed to the main branch rather than a sub-branch making the sequence consistent as we continue to push items into different branches  

## What are the four main steps this workflow performs? 
getting the code from the repository using the name of the checkout code, validating the HTML files by getting the name of the HTML file and its root, checking for broken lines, uploading the site to the github pages 

## What does "checkout code" step do and why is it neccessary? 
Checkout code gets the code from the repository and checks if everything is working approprietly by using 'actions/checkout@v4'

## What is the purpose of the enviorment configuration?
Helps sets target for deployments for security rules to be implemented if triggered 

## How does this automated deployment improve reliability compared to manual deployment? 
it's more reliable because it is more consist compared to manual deployment since we already have a ruleset being implemented 

## What would happen if you pushed code to a different branch? 
Github would flag a code review pending where we are able to make changes make comments, and merge/reject the request to the main branch 