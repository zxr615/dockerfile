FROM docker.elastic.co/elasticsearch/elasticsearch:${ES_VERSION}@sha256:5d8f1962907ef60746a8cf61c8a7f2b8755510ee36bdee0f65417f90a38a0139

RUN sh -c '/bin/echo -e "y" | ./bin/elasticsearch-plugin install https://github.91chifun.workers.dev//https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v${ES_VERSION}/elasticsearch-analysis-ik-${ES_VERSION}.zip'
