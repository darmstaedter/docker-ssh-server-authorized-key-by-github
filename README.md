# docker-ssh-server-authorized-key-by-github

Use in docker-compose.yml:

```
ssh:
  image: darmstaedter/ssh-server-authorized-key-from-github
  tty: true
  volumes_from:
    - container_name
  ports:
    - "1122:22"
```
