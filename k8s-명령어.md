```sh
# default namespace의 pod조회 
kubectl get pods

# 모든 namespace의 pod조회
kubectl get pods --all-namespaces

# pod 정보 자세히 보기 
kubectl get pod -o wide

# pod watch mode로 보기 
kubectl get pod -w

# default namespace의 deployment조회
kubectl get deploy

# 모든 namespace의 모든 deployment조회
kubectl get deploy --all-namespaces

# default namespace의 service조회
kubectl get service
kubectl get svc

# 모든 namespace의 모든 service조회
kubectl get service --all-namespaces
kubectl get svc --all-namespaces

#node 조회
kubectl get node
```
