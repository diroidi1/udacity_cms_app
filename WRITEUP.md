# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*


- for VM  solution 
    + Estimation for Linux B1s 1gb ram and 4 gb memory = US$7.59 per month
    + Pros: we have full control about OS and run what ever processes we want.
    + Cons: we have to update the OS to avoid any vulnerability

- for App service solution
    + Estimation for Linux Basic with 1.75gb ram and 10gb storage = US$13.14 per month
    + Estimation for Linux Free with 1gb ram and 1gb storage = US$0 per month
    + Pros: easy to deploy web app, do not need to maintain the VMs OS, easy to access the log.

- *Choose the appropriate solution (VM or App Service) for deploying the app: I choose the Web app service
- *Justify your choice* https://project-cms-wa.azurewebsites.net/

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

After last section I know how to publish an full python web app using Azure cloud service.
I can easy deploy and manage cost analysis via resource group.

