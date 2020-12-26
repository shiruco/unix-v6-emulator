# unix-v6-container

#### PDP-11 simulator V3.8-1 on Docker container

# build
```
docker build -t unix_v6 .
```

# run
```
docker run -it unix_v6
```

# login
```
docker exec -i -t ${CONTAINER ID} bash 
```

input `unix` after @ and login as root  

![screen image](https://github.com/shiruco/unix-v6-emulator/blob/main/screen.png)  

# logout
input `sync` command three times and [ctrl + e]

```
# sync
# sync
# sync
# [ctrl + e]
```

so, we back to simh console, input `quit` or `q`.
