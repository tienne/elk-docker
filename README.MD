# Docker for Elastic Stack

Docker 를 이용하여 Elastic Stack 띄우기

# Requirements

- docker (docker for windows / docker for mac / linux docker)
- docker-compose

# Usage

```bash
docker-compose up
```

Background Run

```bash
docker-compose up -d
```

Kibana web UI [http://localhost:5601](http://localhost:5601)

- 5000: Logstash TCP input.
- 9200: Elasticsearch HTTP
- 9300: Elasticsearch TCP transport
- 5601: Kibana
