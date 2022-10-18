This is a repo that deploys an application on a kubernetes cluster using Helm.

First we will want to get Helm installed. This can be done on windows using this command: choco install kubernetes-helm

Making sure that you are inside the fleet-app-helm directory you can use this simple command to deploy the application on your cluster: helm install fleet-app fleet-app-helm

This will deploy an application using all the files found inside the templates directory. These template files get all of their variables from the values.yaml file
