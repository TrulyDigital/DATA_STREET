# Deployments Config

## Local - Windows 10

Init application - SFTP server

```env
$ docker compose -f deploy/server-sftp.local.yaml up -d
```

Stop application - SFTP server

```env
$ docker compose -f deploy/server-sftp.local.yaml down
```

## Dev - Ubuntu Server 22.04

Init application - SFTP server

```env
$ docker compose -f deploy/server-sftp.dev.yaml up -d
```

Stop application - SFTP server

```env
$ docker compose -f deploy/server-sftp.dev.yaml down
```

```
$ docker compose -f deploy/server-sftp.local.yam logs
```