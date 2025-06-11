Ynov JPetStore
=================

## Création VM avec orbstack
![SCR-20250611-jwqd.png](images/SCR-20250611-jwqd.png)

## Installer trivy et vérifier les vulnérabilités

![SCR-20250611-kags.png](images/SCR-20250611-kags.png)

## Site fonctionnel 

![SCR-20250611-kgzk.png](images/SCR-20250611-kgzk.png)

## Run on Docker
```
docker build . -t jpetstore
docker run -p 8080:8080 jpetstore
```
or with Docker Compose:
```
docker compose up -d
```

## Try integration tests

Perform integration tests for screen transition.

```
$ ./mvnw clean verify -P tomcat90
```
