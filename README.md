If you have docker installed, then you can follow the instructions to [start a multi-node cluster with Docker Compose](https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html#docker-compose-file). The instructions on that page creates a cluster with 3 nodes + kibana, with SSL certificates, etc. If you want a secure cluster running locally within docker and with multiple nodes, then these are the instructions that you should use!

This example describes setting up a non-secured Elasticsearch cluster with one node and Kibana, which may be useful for some specific cases.

Elasticsearch will be running at localhost:9200 and kibana at localhost:5601. 


