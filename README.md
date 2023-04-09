# NAUKMA K8S

deploy using minikube

- Start minikube
```bash
minikube start
```



- Create deployment
```bash
kubectl apply -f nginx.k8s.yaml
```

- Start tunnel to access service from outside
```bash
minikube tunnel
```

- Get service
```bash
kubectl get svc
```
Copy the EXTERNAL-IP ща nginx-service and paste it in browser

- Delete deployment
```bash
kubectl delete -f nginx.k8s.yaml
```

- Stop minikube
```bash
minikube stop
```
