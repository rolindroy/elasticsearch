# Docker Image for Elasticsearch - 6.6.0


<img src="https://github.com/rolindroy/elasticsearch/blob/master/files/elasticsearch.png" width="400" height="110" />

This is a modified version of elasticsearch docker image.
### What is Elasticsearch ?
Elasticsearch is a distributed, RESTful search and analytics engine capable of solving a growing number of use cases. As the heart of the Elastic Stack, it centrally stores your data so you can discover the expected and uncover the unexpected.



# Usage

```
docker pull rolindroy/elasticsearch:6.6.0
```
## Development mode
Elasticsearch can be quickly started for development or testing use with the following command:
```
docker run -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" rolindroy/elasticsearch:6.6.0

```
## Production mode

For Production mode, See [Install Elasticsearch with Docker](https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html#docker-cli-run-prod-mode)

# Documentation

For more documentation, Please Jump on [Official Github](https://github.com/docker-library/docs/blob/master/elasticsearch/README.md)
