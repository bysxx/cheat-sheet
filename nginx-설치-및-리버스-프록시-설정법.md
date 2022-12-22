```sh
sudo apt-get install nginx
sudo systemctl start nginx
sudo vim /etc/nginx/site-available/default


# server {
#   server_name api.rhea.n-e.kr; # 원하는 도메인 주소를 넣는다. 루트로 하고 싶은 경우는 _를 입력한다.
#   listen 80 ;
#   listen [::]:80 ;
#   location / {
#	  	proxy_pass http://127.0.0.1:3000/;
#	  }
# }
  
sudo systemctl start nginx
```
