# Provisioning an Ingress controller
In order for the provided Ingress resource to work, your Kubernetes cluster must have an ingress controller running. The Atlassian Helm charts have been tested with the [NGINX Ingress Controller](https://kubernetes.github.io/ingress-nginx/), however [alternatives can also be used](https://kubernetes.io/docs/concepts/services-networking/ingress-controllers/#additional-controllers). 

Here is an example of how these controllers can be installed and configured for use with the Atlassian Helm charts:

* [NGINX Ingress Controller](INGRESS_NGINX.md)

***
* Go back to the [prerequisites](../../PREREQUISITES.md)
* Go back to the [installation guide](../../INSTALLATION.md)
* Go back to [README.md](../../../README.md)
