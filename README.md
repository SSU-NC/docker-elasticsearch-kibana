# Docker Elasticsearch Kibana

## Version
```
ElasticSearch: 7.6.1
Kibana: 7.6.1
```

## Run
* Start container
```sh
$ sudo docker-compose up
```
  
* Stop container
```sh
$ sudo docker-compose down
```

## Port Forwarding
|Host|Container|Service|
|:---:|:---:|:---:|
|9200|9200|elasticsearch|
|5601|5601|kibana|

## Setting
You can set `Elastcisearch` JVM Heap size options. This docker-compose file is set to `8GB` by default.
```
"ES_JAVA_OPTS=-Xms8g -Xmx8g"
```
