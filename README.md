# personal-dockerfiles
Dockerfiles for building personal development images

### Docker commands
```
 docker build -t yifengdev/keras-jupyter:latest .build/
 docker tag yifengdev/base-conda:latest yifengdev/base-conda:v1.0
 docker run --gpus all -p 8888:8888 -it --name my-container -v /path/to/local/folder:/path/in/container yifengdev/keras-jupyter bash
 docker push yifengdev/keras-jupyter
 docker exec -it dlenv bash
 docker exec -u root -it dlenv bash
 passwd deepL
```
