# docker-norikra
docker norikra

``` sh
docker build -t dockerfile/norikra --no-cache --rm=true ./
docker run --name norikra -p 26578:26578 -p 26571:26571 -itd dockerfile/norikra
```
