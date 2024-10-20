**Docker Commands Used in Powershell**

* Starting docker and creating a new conatiner with a specific "image" (operating system version) that you choose in the command (new docker container name and hash will be generated from command):

```
docker run -it ubuntu
```

Once inside ubuntu i realized the git command could not be installed because the os had to first be updated ```apt update``` | Then git could be installed w/ ```apt install git```

* How would i start and attatch to a docker container i already have created and worked in before:

If the container is stopped, first start it with ```docker start <container_name_or_id>```

If the container is running, and want to stop it with ```docker stop <container_name_or_id>```

Then attatch to it interactivly ```docker attach <container_name_or_id>```

* Bonus Commands found

View container logs, To see the output of a running container without attaching to it ```docker logs <container_name_or_id>```

Inspect container details To view detailed information about the container ```docker inspect <container_name_or_id>```
