# Overview

Overview of different repositories on [Trading Strategy](https://tradingstrategy.ai) Github organisation

- client is [tradingstrategy Python package](https://pypi.org/project/tradingstrategy/) for creating trading algorithms
- trade-executor is a Python based command daemon for executing strategies on decentralised exchanges and active portfolio management tool
- eth-hentai is a [Python library to easily interact with decentralised exchanges](https://pypi.org/project/eth-hentai/)
- frontend is [Trading Strategy website](https://tradingstrategy.ai) written in [SvelteKit framework](http://kit.svelte.dev/) 
- theme is [Bootstrap 4 based theme](https://getbootstrap.com/docs/4.0/getting-started/introduction/) for the frontend
- spec is an [OpenAPI 3](https://swagger.io/specification/) based specification for backend APIs
- search is [Typesense backend](https://typesense.org/) for token and trading pair search
- proxy-server is [Caddy](https://caddyserver.com/) reverse proxy for [tradingstrategy.ai](https://tradingstrategy.ai) domain
- logging is [ELK (Elastic + Logstash + Kibana)](https://aws.amazon.com/opensearch-service/the-elk-stack/) hosted service to manage logs 
- monitoring is a collection of Datadog alert scripts
- (private) oracle is the Python based oracle core that interacts with blockchains and TimescaleDB
- (private) backend is a [Pyramid web framework](https://trypyramid.com/) based API server that runs [tradingstrategy.ai](https://tradingstrategy.ai) website
