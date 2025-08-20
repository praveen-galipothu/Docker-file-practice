### ENTRYPOINT
ENTRYPOINT is also used run the container just like CMD. but there are few differences 
1. we cant override ENTRYPOINT, but we override CMD
2. we cant override ENTRYPOINT, if we do so it will go and append to the ENTRYPOINT command