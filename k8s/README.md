# Cheatsheet Kubernetes

## Kubectl

* Apply config  
```kubectl apply -f etc/k8s/deployment.yaml```

### Crud commands
```kubectl create deployment [name]```  
```kubectl edit deployment [name]```  
```kubectl delete deployment [name]```  

### Get status of different components
```kubectl get [nodes/deployment/pod/services/replicaset]```

### Debugging pods
* Log to console  
```kubectl logs [pod name]```

* Get interactive terminal (-it)  
```kubectl exec -it [pod name] -- bin/bash```
