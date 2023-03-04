```sh
lsblk # 로 모든 디스크 조회
sudo growpart /dev/nvme0n1 1 # 증설하고 싶은 디스크 선택
df -hT # 로 ext4 인지, XFS 인지... 확인
sudo resize2fs /dev/root # ext4 는 resize2fs 로 늘릴 수 있음
```
