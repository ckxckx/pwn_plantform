# pwn_plantform
## howtouse:
可能需要的命令
```
  docker-compose up -d 
  docker ps
  docker ps -a
  docker rm -f $(docker ps -aq)
  docker images
  docker rmi -f  image-id
```
### 使用方法
> 将share中的elf文件替换成题目，修改run.sh，多题目环境修改.yml文件中的ports，避免端口占用

