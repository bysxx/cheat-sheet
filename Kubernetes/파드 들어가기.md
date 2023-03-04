```sh
# Pod에 bash로 들어가기
kubectl exec -it POD_NAME /bin/bash

# 특정 Pod에서 curl 실행하기
kubectl exec POD_NAME -- curl localhost:8080
```
