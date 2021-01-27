# gravitee-grafana

Provide Grafana dashboard for Elasticsearch analytics

Need to create 3 Elasticsearch datasources.
this dashboard allow dynamic DS if you have several g.io analytics environments.

* gravitee-{{env}}-health
* gravitee-{{env}}-monitor
* gravitee-{{env}}-request

up to you to change this strategy.

Dynamically Scale row and panels according to router gateway node number.

To use this dashboard, import it directly in Grafana with import feature on the main dashboard page.

