# Pod

```bash
kubectl create -f myapp-pod.yaml
kubectl apply -f myapp-pod.yaml
```

```bash
kubectl get pods
```

```bash
kubectl get pod myapp-pod -o wide
```

```bash
kubectl get pod myapp-pod -o yaml
kubectl get pod myapp-pod -o json
```

```bash
kubectl describe pod myapp-pod
```

```bash
kubectl logs myapp-pod
kubectl logs pod/myapp-pod
```

```bash
kubectl port-forward myapp-pod 8080:8080 # 내가 배포한 pod로 포트포워딩 해줌.
kubectl port-forward pod/myapp-pod 8080:8080
```

```bash
kubectl delete -f myapp-pod.yaml
```
