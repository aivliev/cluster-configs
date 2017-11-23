Docker-compose file for infrastructure setup:
1. docerk registry
2. docker registry UI
3. postgresql server
4. Keycloak 


Require in each .env file:

```
#url for docer registry to get images from and point local registry - i.e. docker.example.com
__DOCKER_REGISTRY=
#root hostname - i.e. example.com
__HOST_HOSTNAME=
```

in .env_psgr
```
#Full path for persistent folder for posgres data
__POSTGRES_DB_FLD=
#Full path for persistent folder for postgres tablespace
__POSTGRES_TS_FLD=
```
