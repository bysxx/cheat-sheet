```sh
sudo fallocate -l 4G /swapfile
sudo chmod 600 /swapfile
sudo mkswap /swapfile
sudo swapon /swapfile

vim /etc/fstab
# ▼ 아래 코드를 파일의 맨 마지막에 붙혀넣고 저장한다
# /swapfile swap swap defaults 0 0
```

VM 이미지를 ubuntu minimal로 설정 할 경우, 기본적으로 메모리 스왑이 설정되어있지 않다.

위 명령어들을 이용하여 메모리 스왑을 설정하자.
