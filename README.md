# Crossplane
This README documents the Crossplane integration as Nirmata add-on on Kubernetes clusters.

### What is the CrossPlane?
Crossplane is a framework for building cloud native control planes without needing to write code. It has a highly extensible backend that enables you to build a control plane that can orchestrate applications and infrastructure no matter where they run, and a highly configurable frontend that puts you in control of the schema of the declarative API it offers.

### How do I get set up Crossplane?
1. Clone this repository or add its contents to your own private Git repository.
2. Create a Nirmata catalog application with a Git upstream and select the Crossplane repository. In Directory list, select crossplane. You can optionally select the kustomization.
3. Edit the catalog application and select an add-on category (e.g. Other). This is required to select the application as an add-on.
4. Update a Cluster Type, or create a new one, and select the Crossplane add-on application in the "Add-Ons" section.Ensure that the namespace you use is "**crossplane-system**"
5. Create clusters using the cluster type.
6. If the addon is to be added to a running cluster, create an namespace with the name "**crossplane-system**" and choose this environment while deploying the application
7. Verify that the application is running in Nirmata. 

### How to add AWS Provider in Crossplane?
1. Clone this repository or add its contents to your own private Git repository.
2. Create a Nirmata catalog application with a Git upstream and select the Crossplane repository. In Directory list, select Providers/AWS You can optionally select the kustomization.
3. Edit the catalog application and select an add-on category (e.g. Other). This is required to select the application as an add-on.
4. Update a Cluster Type, or create a new one, and select the Crossplane add-on application in the "Add-Ons" section.Ensure that the namespace you use is "**crossplane-system**"
5. Create clusters using the cluster type.
6. If the addon is to be added to a running cluster, create an namespace with the name "**crossplane-system**" and choose this environment while deploying the application
7. Verify that the application is running in Nirmata.

### Who do I talk to?
For issues, contact support@nirmata.com

