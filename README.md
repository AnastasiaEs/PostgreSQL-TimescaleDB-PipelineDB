# PostgreSQL-TimescaleDB-PipelineDB

PostgreSQL + TimescaleDB + PipelineDB docker image 🐘📈🔀

Based on [Alpine Linux](https://alpinelinux.org).

Docker image with:
* [PostgreSQL](https://www.postgresql.org/)
* [TimescaleDB](https://www.timescale.com/)
* [PipelineDB](https://www.pipelinedb.com/)

Current versions of components:
* PostgreSQL: **11.3** ([Source docker image](https://store.docker.com/images/postgres))
* TimescaleDB: **1.3.0** ([Release archive](https://github.com/timescale/timescaledb/releases/tag/1.3.0))
* PipelineDB: **1.0.0-13** ([Release archive](https://github.com/pipelinedb/pipelinedb/releases/tag/1.0.0-13))

How to build using `docker-compose`:

```bash
$ docker-compose build
```

How to run:

```bash
$ docker-compose up -d
```
