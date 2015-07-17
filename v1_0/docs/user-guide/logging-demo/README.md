---
layout: docwithnav
---
<!-- BEGIN MUNGE: UNVERSIONED_WARNING -->


<!-- END MUNGE: UNVERSIONED_WARNING -->
# Elasticsearch/Kibana Logging Demonstration
This directory contains two [pod](../../../docs/user-guide/pods.html) specifications which can be used as synthetic
logging sources. The pod specification in [synthetic_0_25lps.yaml](synthetic_0_25lps.yaml)
describes a pod that just emits a log message once every 4 seconds. The pod specification in
[synthetic_10lps.yaml](synthetic_10lps.yaml)
describes a pod that just emits 10 log lines per second.

To observe the ingested log lines when using Google Cloud Logging please see the getting
started instructions
at [Cluster Level Logging to Google Cloud Logging](../../../docs/getting-started-guides/logging.html).
To observe the ingested log lines when using Elasticsearch and Kibana please see the getting
started instructions
at [Cluster Level Logging with Elasticsearch and Kibana](../../../docs/getting-started-guides/logging-elasticsearch.html).


<!-- BEGIN MUNGE: GENERATED_ANALYTICS -->
[![Analytics](https://kubernetes-site.appspot.com/UA-36037335-10/GitHub/docs/user-guide/logging-demo/README.md?pixel)]()
<!-- END MUNGE: GENERATED_ANALYTICS -->