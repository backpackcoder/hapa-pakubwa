# hapa-pakubwa
Software to support our Mission trip to Mbeya, Tanzania in 2016.


## website

Create the docker container locally using

```bash
docker build -t website .
docker run --name web1 -p 80:80 -p 443:443 -v ~/keys:/etc/nginx/ssl website
```