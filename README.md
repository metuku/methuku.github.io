# Running in dev machne

## Prerequisite

1. `docker`
2. `docker-compose`

> NOTE : `docker` need to have all the permisions of the user. To get permisions run `sudo usermod -a -G docker $USER`, reboot the machine

## RUN

```bash
cd wsrepo/methuku/

docker-compose up -d
```

Application will be running on port `4000`