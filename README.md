## Introduction to EFK stack
When running multiple services and applications on a Kubernetes cluster, a centralized, cluster-level logging stack can help you quickly sort through and analyze the heavy volume of log data produced by your Pods. One popular centralized logging solution is the EFK stack. Together Elasticsearch, Filebeat, and Kibana are commonly referred to as the EFK stack.

**Elasticsearch:** An object store where all logs are stored.
**Fluentd:** Gathers logs from nodes and feeds them to Elasticsearch.
**Kibana:** A web UI for Elasticsearch.

## Steps to deploy EFK stack on Kubernetes cluster using Helm charts
With the need for fast software development and delivery, we can deploy them easily using Helm charts. 
https://medium.com/@vinodkrane/deploy-an-efk-stack-to-kubernetes-7796e839864c
