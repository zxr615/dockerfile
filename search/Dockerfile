FROM docker.elastic.co/elasticsearch/elasticsearch:7.10.1@sha256:5d8f1962907ef60746a8cf61c8a7f2b8755510ee36bdee0f65417f90a38a0139

ENV ES_VERSION=7.10.1

RUN sh -c '/bin/echo -e "y" | ./bin/elasticsearch-plugin install https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v$ES_VERSION/elasticsearch-analysis-ik-${ES_VERSION}.zip'
RUN ./bin/elasticsearch-plugin install https://github.com/medcl/elasticsearch-analysis-pinyin/releases/download/v${ES_VERSION}/elasticsearch-analysis-pinyin-${ES_VERSION}.zip 

