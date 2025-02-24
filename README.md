# Infra for local development

## Purpose
To be able to quickly spin up various stacks for local development.

## Options
- Docker (Preferred)
	- Dockerfiles
	- Docker Compose Scripts
- Virtual machine 
- Installation on the local system 
	- For python always use virtual environments. Use `uv`

## List
- Current 
	- Atoms 
		- Postgres
		- ELK 
		- Mongo
		- Redis
		- OpenSearch 
		- RabbittMQ
		- Neo4J
	- Applications 
		- Airbyte 
		- Metabase 
		- Supabase
		- Ghost 
		- Wordpress 
	- Others 
		- Firecrawl 
		- Browseruse 
- TODO 
	- Reverse Proxy 
		- Nginx
	- CICD related 
    	- Jenkins 
    	- (Security related)
	- Container Managment - 
		- Portainer 
		- Docker Logs 
		- Docker Security 
	- Cloud services
		- Minio
		- LocalStack 
	- Monitoring (Prometeus, Grafana etc) 
		- Prometheus 
		- Grafana 
		- Loki (For Logs)
		- (Include logging, application monitoring, open telemetry etc.)