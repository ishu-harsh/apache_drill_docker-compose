# apache_drill_docker-compose

Distributed mode installation of Acpache Drill - Docker compose file 


## Docker Installation

```
docker run -it --name drill \
	-p 8047:8047 \
	-p 31010:31010 \
	-v /home/ifserveradmn/if-studio/apache-drill-data:/mnt \
	apache/drill
```



## Running Acpache in distributed mode using docker compose 

```
docker-compose -f distributed-mode.yaml up -d
```
