# Cheatsheet Kubernetes

## KubeCTL

[Back to cheatsheet index](../README.md)  
[Layers of abstraction](layers-of-abstraction.md)

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
```kubectl get [nodes/deployment/replicaset/pod/services]```

### Debugging
* ```kubectl get event```
* ```kubectl describe [nodes/deployment/replicaset/pod/services] [name]```

### Pods
* Log to console  
```kubectl logs [pod name]```

* Get interactive terminal (-it)  
```kubectl exec -it [pod name] -- bin/bash```

* Get info about pod
```kubectl describe pod [pod name]```

* ```kubectl cluster-info dump```

## Sources
Cheatsheet provided by Kubernetes: https://kubernetes.io/docs/reference/kubectl/cheatsheet  
Troubleshooting deployments: https://learnk8s.io/troubleshooting-deployments  
Troubleshooting flow: https://learnk8s.io/a/a-visual-guide-on-troubleshooting-kubernetes-deployments/troubleshooting-kubernetes.v2.pdf
