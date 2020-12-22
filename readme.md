# Elastic Stack Index Patterns for Time Series Data

Demo for Elastic's 2021 advent blog post [Index-Patterns und ihre Tradeoffs für Logs, Metriken und Traces (German)](https://discuss.elastic.co/t/dec-22nd-2020-de-index-patterns-und-ihre-tradeoffs-fur-logs-metriken-und-traces/).

Each folder demonstrates the default Filebeat configuration for that specific Elastic Stack version and you can try it out with `docker-compose up`. It starts Elasticsearch, Kibana, and Beats with the [Elasticsearch module](https://www.elastic.co/guide/en/beats/filebeat/current/filebeat-module-elasticsearch.html) enabled through index hints.

For a more detailed description, please see the blog post.
