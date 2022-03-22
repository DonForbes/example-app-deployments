# example-app-deployments

Some sample yaml deployment files to test out basic kubernetes access.

Firstly create a docker-secret in the namespace you want to use.

```
kubectl create secret docker-registry -n don docker-secret --docker-username=donaldf --docker-server=docker.io --docker-password=<secret>
```
  
# Example deployment of a yaml file

```
kubectl -n don apply -f https://raw.githubusercontent.com/dforbes-pivotal/example-app-deployments/main/nginx/nginx.yaml
```
