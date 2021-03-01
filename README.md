# QuickStart OpenLdap in docker

```
In order to get started with interacting with an LDAP-server
As a Software Engineer
I want to have a easy quick-startable LDAP-server.
```

1. Check out this repo
2. Make the needed local directories
3. Start the server
4. Connect to the server



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

Use an LDAP-client and use the following value to create a connection:

* Server: localhost
* Port: 389
* cn: 'cn:admin,dc=infi,dc=nl'
* Password: 'IetsGeheims' 

Recommended LDAP-Client: [Apache Directory Studio](https://directory.apache.org/studio/) (Does require Java11)
