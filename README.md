# docker_lessons

## 1. save locally:
`docker save --output [your directory]`
## 2. load the image:
`docker load --input [your directory]`
## 3. start this image:
`docker start [container ID]`
* Note: To find contaier ID, use `docker ps`
## 4. use bash:
`docker exec -it [container ID] bash`
## 5. save changes:
`docker commit [container name]`
