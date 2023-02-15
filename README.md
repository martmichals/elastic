# Elastic

Repository with files for learning about Elasticsearch.

## Installation

Instructions for installation on a Linux machine.

Elasticsearch:

```bash
wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-8.6.1-linux-x86_64.tar.gz
wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-8.6.1-linux-x86_64.tar.gz.sha512
shasum -a 512 -c elasticsearch-8.6.1-linux-x86_64.tar.gz.sha512
tar -xzf elasticsearch-8.6.1-linux-x86_64.tar.gz
cd elasticsearch-8.6.1/
```

Kibana:

```bash
curl -O https://artifacts.elastic.co/downloads/kibana/kibana-8.6.1-linux-x86_64.tar.gz
curl https://artifacts.elastic.co/downloads/kibana/kibana-8.6.1-linux-x86_64.tar.gz.sha512 | shasum -a 512 -c -
tar -xzf kibana-8.6.1-linux-x86_64.tar.gz
cd kibana-8.6.1/
```
