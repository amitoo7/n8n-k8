# n8n-k8

### How to Setup n8n on your Cluster

``` 
    kubectl apply -f n8n-postgres.yaml
    kubectl apply -f n8n-secrets.yaml
    kubectl apply -f n8n-deployment.yaml
    kubectl apply -f n8n-service.yaml 
```
If you want to change the postgres credentials you can change it in *n8n-postgres.yaml*
and make sure you change the same in *n8n-secrets.yaml* also.
