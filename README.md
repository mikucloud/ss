```
curl -fsSL https://github.com/mikucloud/ss/raw/master/install.sh | bash -s API TOKEN NODEID LICENSE 60
```


```
docker run -d --name=ss \
-v /root/.cert:/root/.cert \
-e API=授权地址 \
-e TOKEN=通讯密钥 \
-e NODE=节点ID \
-e LICENSE=授权码 \
-e SYNCINTERVAL=60 \
--restart=always \
--network=host \
mikucloud/tidalab-ss
```
