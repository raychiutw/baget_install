# baget_install

```
docker run -d --restart always --name nuget-server -p 5555:80 --env-file baget.env -v "baget-data:/var/baget" loicsharma/baget:latest
```
