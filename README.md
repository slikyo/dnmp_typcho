```
git clone https://github.com/slikyo/dnmp_typcho.git
docker-compose up -d
cd www
wget http://typecho.org/downloads/1.1-17.10.30-release.tar.gz
tar xvzf 1.1-17.10.30-release.tar.gz
mv build typecho
rm 1.1-17.10.30-release.tar.gz  
```

进入typecho 页面配置后，
数据库地址为172.20.2.100，默认数据库密码为123456，可以自行到docker-compose修改。

