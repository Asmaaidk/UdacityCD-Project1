# Deploy An Article CMS to Azure


### Comparing VM and App Service

*Cost*

VM: only charged on disk costs when stopped but can cost more since it provides more for the developer
App Service: will continue charging even though apps are unused or when stopped but based on the plan it cost less especially for an app like the one in this project

*Scalability*

VM: horizontal scaling is achieved via Scale Sets
App Service: provides an integrated load balancer 

*availability*

VM: It gives full control over computing environment
App Service: it allows to integrate the app without managing the underlying infrastructure

*workflow*

VM: Uses an OS image
App Service: Uses a runtime stack

### The appropriate resource option for deploying this app

App Service will be more approprite for the app for couple of resons:
 - Lightweight APIs tend to be well-suited to App Services over VMs
 - App Services cost less than VMs do
 - The app dosen't need to scale quickly 

### App changes that would make VM a better choice

- If the app had more functionalities or added more features to the point of requiring vertical scaling.
- Maybe a vast increase of users numbers
