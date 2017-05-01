# Notes on Google Cloud Platform and Kubernetes

The base configuration for Kubernetes is generated by the [kompose](http://kompose.io/) tool from the default docker-compose.yml file (which is the deployment, not development configuration).

Secrets for deployment should be stored in a seperate yml that is NOT commited to github.
