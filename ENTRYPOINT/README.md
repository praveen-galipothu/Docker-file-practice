### ENTRYPOINT
ENTRYPOINT is also used run the container just like CMD. but there are few differences 
1. we cant override ENTRYPOINT, but we override CMD
2. we cant override ENTRYPOINT, if we do so it will go and append to the ENTRYPOINT command
3. if you use CMD and ENTRYPOINT and dont give any command from terminal, CMD act as argument provider to ENTRYPOINT
4.CMD will supply defualt argument to the ENTRYPOINT.
5. you can always override CMD argument from runtime.
6. you can stop misusing your image with other commands.