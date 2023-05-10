# Docker

## huge image

- check if add .dockerignore https://stackoverflow.com/q/26600769/3493127 。

## Networks

Docker container 預設的網路模式是 bridge mode ，要 access 原本的 localhost 需要用 ip addr show docker0 取得 ip ，並用 ip access 特定的 localhost port [參考資料](https://bright-softwares.com/blog/en/docker/how-do-i-access-the-host-port-in-a-docker-container)。
