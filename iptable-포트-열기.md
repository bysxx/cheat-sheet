```sh
sudo apt-get install iptables-persistent
sudo iptables -I INPUT 1 -p tcp --dport 80 -j ACCEPT
sudo netfilter-persistent save
sudo iptables --list
```

Reference: https://blog.dalso.org/article/%EC%98%A4%EB%9D%BC%ED%81%B4-%ED%81%B4%EB%9D%BC%EC%9A%B0%EB%93%9C-%EB%B0%A9%ED%99%94%EB%B2%BD-%EC%84%A4%EC%A0%95%ED%95%98%EA%B8%B0
