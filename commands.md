Create namespace:
```
kubectl create namepsace prod
```
Rolling Update:
```
kubectl set image deployment/nginx-deployment nginx-container=nginx:1.17
```
Rollback to the Previous Revision:
```
kubectl rollout undo deployment/nginx-deployment
```
