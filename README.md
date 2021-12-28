# Lab11_deploy_to_k8s
Deploy web-app to k8s cluster


### Steps 
```
PROJECT_ID="my-shop-project-123" - create env
kubectl create ns my-shop
kubectl apply -n my-shop -f ./release/kubernetes-manifests.yaml
```
