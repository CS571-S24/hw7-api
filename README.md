build
```bash
docker build . -t ctnelson1997/cs571-s24-hw7-api
docker push ctnelson1997/cs571-s24-hw7-api
```

run
```bash
docker pull ctnelson1997/cs571-s24-hw7-api
docker run --name=cs571_s24_hw7_api -d --restart=always -p 58107:58107 -v /cs571/s24/hw7:/cs571 ctnelson1997/cs571-s24-hw7-api
```

run fa
```bash
docker pull ctnelson1997/cs571-s24-hw7-api
docker run --name=cs571_fa_s24_hw7_api -d --restart=always -p 59107:58107 -v /cs571_fa/s24/hw7:/cs571 ctnelson1997/cs571-s24-hw7-api
```