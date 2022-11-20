# Docker update
**There are some new libreries required for this session**, then, please update the container by the running the following commands inside this folder:

```
docker build -t YourNickName/jupyter-ai:0.1  .
```

now, run the container using:
```
docker run -it -v `pwd`:/home -p 8888:8888 YourNickName/jupyter-ai:0.1 bash
root@8130c6df985a:/# 
```

The container will run now automatically the jupyer-notebook instance