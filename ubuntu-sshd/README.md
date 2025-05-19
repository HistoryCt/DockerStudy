```
docker build --build-arg ROOT_PASSWORD=yourpassword -t ubuntu-sshd .

docker run -e ROOT_PASSWORD=yourpassword -p 2222:22 ubuntu-sshd
```