```sh
# test.yaml파일 작성 후 create하면 yaml 파일의 내용이 생성
kubectl create -f test.yaml 

# yaml파일의 문법이 맞는지 확인하기 
kubectl create -f test.yaml --dry-run=client

# 명령어로 create 후 yaml 파일로 만들기
kubectl create deploy test-deploy --image=nginx --dry-run=client -o yaml > nginx.yaml
```
