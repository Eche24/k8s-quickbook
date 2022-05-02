Pod

```sh
kubectl get pods
```


Viewing log in k8s

 ```sh
 kubectl logs <name>
 ```

 Monitoring with metrics-server..
 Thing to monitor for: 
    CPU,
    Memory,
    Health state,
    network,
    disk utilization,
    pods performance metric,
```sh
 clone metric server from github
 ```

```sh
 kubectl top <node>
 ```
```sh
 kubectl top <pod>
 ```

 ### Application lifecycle Management
 #### Deployment strategy
 Recreate and rolling-update
 ```sh
 kubectl rollout status deployment/<name>
 ```

```sh
 kubectl history rollout
```
Rollback
```sh
 kubectl rollout undo deployment/<name>
 ```