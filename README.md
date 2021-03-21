# Confluence Cloud Metrics Exporter for Datadog

![GitHub repo size](https://img.shields.io/github/repo-size/bramvdklinkenberg/ccloud-metrics-exporter)
![GitHub contributors](https://img.shields.io/github/contributors/bramvdklinkenberg/ccloud-metrics-exporter)
![GitHub stars](https://img.shields.io/github/stars/bramvdklinkenberg/ccloud-metrics-exporter?style=social)
![Twitter Follow](https://img.shields.io/twitter/follow/BramKlinkenberg?style=social)

With the the Confluent Cloud Metrics Exporter deployment you can fetch [metrics](https://docs.confluent.io/5.5.0/cloud/metrics-api.html#list-the-available-metrics "available metrics") from Confluent Cloud and Export them to Datadog.

## Prerequisites/ Assumptions

Before you begin, I assume you have the following in place:
* A kubernetes cluster
* A [datadog](https://www.datadoghq.com/) account
* A kafka cluster running in [confluent cloud](https://www.confluent.io/confluent-cloud/)

## Installing the Confluent Cloud Metrics Exporter

```
kubectl apply -f ccloud-metrics-exporter.yaml
```

## Contributing to the Confluent Cloud Metrics Exporter
<!--- If your README is long or you have some specific process or steps you want contributors to follow, consider creating a separate CONTRIBUTING.md file--->
To contribute to the Confluent Cloud Metrics Exporter, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.
