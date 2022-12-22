```sh
sudo snap install --classic certbot
sudo certbot --nginx
sudo certbot renew --dry-run # 수동 갱신하기. 근데 어차피 수동 갱신 안해줘도 60일마다 자동 갱신된다. cronjob 이라도 도나?
```

이 작업을 하기전에 리버스 프록시 설정을 다 해놓고, 도메인까지 연결시켜 놓는게 좋다.
