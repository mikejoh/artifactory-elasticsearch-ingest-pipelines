# Artifactory Elasticsearch Ingest pipelines

_In this example i've used Filebeat to send Artifactory logs to Elasticsearch, before indexing happens Ingest pipelines will parse the incoming documents to extract relevant fields._

## Resources

* If you want a quick rundown on how Ingest pipelines works check this [repository](https://github.com/mikejoh/elasticsearch-ingest-pipeline-examples) out.
* Official documentation on the Ingest node type and pipelines can be found [here](https://www.elastic.co/guide/en/elasticsearch/reference/6.4/ingest.html)
* Official documentaion on Filebeat can be found [here](https://www.elastic.co/guide/en/beats/filebeat/current/filebeat-getting-started.html)

## Environment

This have been tested using:
* Artifactory 6.3.3
* Elasticsearch 6.4.0
* Filebeat 6.4.0

## Step-by-step

1. Create the pipelines
2. Install and configure Filebeat
3. Test the pipelines offline
4. Run Filebeat

