### CMD
CMD is the instruction that run the container
### RUN vs CMD
*RUN command will execute at the time of image creation
*CMD command will execute at the time of running container
q) How to delete all the containers at a time?
a) by using #docker ps -a -q, we can list out all the containers, then by using #docker rm -f 'docker ps -a -q'