# Kubernetes Cluster Basic Stack

This repository aims to be a basic cluster example

## Continuous Deployment

This cluster uses the [App of Apps pattern](https://argo-cd.readthedocs.io/en/stable/operator-manual/cluster-bootstrapping/#app-of-apps-pattern).

To add a new application to the cluster all you have to do is add an [Application](https://argo-cd.readthedocs.io/en/stable/operator-manual/declarative-setup/#applications) resource and it will added to ArgoCD managed applications.
