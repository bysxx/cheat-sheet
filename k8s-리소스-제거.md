```sh
# 파일 기반 삭제
kubectl delete -f test.yaml

# 모든 자원 삭제 
kubectl delete all --all

# 원하는 파드만 삭제 
kubectl delete POD_NAME

# 특정 네임스페이스 모든 파드 삭제
kubectl delete --all pods --namespace=NAMESPACE_NAME
```
