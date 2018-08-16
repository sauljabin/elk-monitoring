# ELK Monitorig

This is a project to learn how to monitor applications with elk.
This is not for production, it is to test the integration.

### Links

- Project Base [https://github.com/deviantony/docker-elk](https://github.com/deviantony/docker-elk)
- ELK Stack [https://www.elastic.co/elk-stack](https://www.elastic.co/elk-stack)

### Getting started

```
make init up
```

### Commands

`make build` creates containers

`make up` runs compose

`make up-d` runs daemon compose

`make down` stops the application

`make delete` deletes containers

`make show` shows the current containers (needs `up`)

`make init` starts the configuration

### ELK Information

Give Kibana a few seconds to initialize, then access the Kibana web UI by hitting
[http://localhost:5601](http://localhost:5601) with a web browser.

By default, the stack exposes the following ports:
* 5000: Logstash TCP input.
* 9200: Elasticsearch HTTP
* 9300: Elasticsearch TCP transport
* 5601: Kibana