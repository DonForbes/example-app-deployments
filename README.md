# example-app-deployments

Some sample yaml deployment files to test out basic kubernetes access.

Firstly create a docker-secret in the namespace you want to use.

```
kubectl create secret docker-registry -n don docker-secret --docker-username=donaldf --docker-server=docker.io --docker-password=<secret>
```
  
