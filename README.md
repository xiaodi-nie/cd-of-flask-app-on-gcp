# Continuous Deployment of Flask Application on GCP
This project implements continuous deployment using Google's Cloud Build service. A simple flask application will be deployed to App Engine everytime a new push happens in this github repo. It is done through Cloud Source Repositories and they are private Git repositories hosted on Google Cloud. These repositories let you develop and deploy an app or service in a space that provides collaboration and version control for your code.


### Create new Git repo
First we need a new github repo. We will later sync Cloud Source Repositories to this repo to enable continuous build and deploy.

### Clone repo to GCP cloud shell
