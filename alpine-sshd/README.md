构建镜像：
```sh
docker build -t alpine-sshd .
```

运行容器并设置 root 密码（例如设置为 mypassword）：
```sh
docker run -e ROOT_PASSWORD=mypassword -p 2222:22 alpine-sshd
```