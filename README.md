# clickhouse-docker
Single node clickhouse node 

```
root@docker:~/inception_infra/clickhouse-docker# docker-compose up -d
Creating network "clickhouse-docker_my-network" with driver "bridge"
Creating clickhouse111 ... done
root@docker:~/inception_infra/clickhouse-docker#
root@docker:~/inception_infra/clickhouse-docker#
root@docker:~/inception_infra/clickhouse-docker# docker-compose ps


    Name           Command       State                                              Ports
-------------------------------------------------------------------------------------------------------------------------------------
clickhouse111   /entrypoint.sh   Up      0.0.0.0:8114->8123/tcp,:::8114->8123/tcp, 0.0.0.0:9111->9000/tcp,:::9111->9000/tcp, 9009/tcp
root@docker:~/inception_infra/clickhouse-docker#
```
