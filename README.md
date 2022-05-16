# Kubernetes distributed voting app

Example of a distributed voting app running on Kubernetes.

After cloning, run the following commands on your cluster

```
kubectl create -f namespaces --save-config --record

kubectl create -f deployments --save-config --record

kubectl create -f services --save-config --record
```

Check it out

```
kubectl get all -n vote
```


