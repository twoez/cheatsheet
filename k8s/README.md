# Cheatsheet Kubernetes

## KubeCTL
https://kubernetes.io/docs/reference/kubectl/cheatsheet/

### Using configuration file
* Apply config  
```kubectl apply -f [file name]```

* Delete config  
```kubectl delete -f [file name]```

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

* Get info about pod
```kubectl describe pod [pod name]```
