#PODS
#Deploy the Pod in the available nodes

```
kubectl apply -f pod.yml 
```
pod/my-jenkins created

#List all the Pods
```
kubectl get pods
```
NAME         READY   STATUS    RESTARTS   AGE
my-jenkins   1/1     Running   0          6s

#List all the pods with detailed Output
```
kubectl get pods -owide
```
NAME         READY   STATUS    RESTARTS   AGE   IP             NODE                                       NOMINATED NODE   READINESS GATES
my-jenkins   1/1     Running   0          12s   10.244.166.4   ip-10-0-0-209.us-west-1.compute.internal   <none>           <none>
