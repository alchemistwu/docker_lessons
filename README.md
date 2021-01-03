# docker_lessons

## 1. save locally:
`docker save --output [your directory]`
## 2. load the image:
`docker load --input [your directory]`
## 3. run an image:
`docker run --gpus all -it [Image ID]`
* Note: use `docker images` to find image ID.
## 4. commit changes:
`docker commit [Container ID] [Saving name]`
* Note: use `docker ps` to find Container ID
