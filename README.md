# QuickStart OpenLdap in docker

## Make directories for volume mounts
```sh
mkdir data
mkdir slapd.d
```

[https://docs.docker.com/docker-for-mac/#file-sharing](https://docs.docker.com/docker-for-mac/#file-sharing)


# Start the container:

```sh
docker-compose up
```



# Connect to the container

* localhost
* Port: 389
* cn: 'cn:admin,dc=infi,dc=nl'
* Password: 'IetsGeheims' 
