# Instructions
In order to deploy the doris connector, you need some secrets set:

```
kubectl create secret generic doris-api-key --from-literal=api-key=dummy  --namespace sunetrds
kubectl create secret generic doris-s3-key --from-literal=s3-key=dummy  --from-literal=api-key=dummy --namespace sunetrds
kubectl create secret generic doris-s3-secret --from-literal=s3-secret=dummy  --namespace sunetrds
```
