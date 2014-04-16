## 下記の gist を /etc/motd に貼り付けることで可能です
※debian系なら /etc/motd.tail にどうぞ

### docker logo
![](./images/docker-logo.jpg)

[gist:docker.txt](https://gist.githubusercontent.com/makocchi-git/9936457/raw/7b358b4b8cbb730bd99c8fb5d6e273826ac3f290/docker.txt)

コンテナ内にloginするとかあまり無いですけどね・・・

### こんな感じでどうぞ
```bash
$ curl -s <gistのurl> | sudo tee -a /etc/motd
```
