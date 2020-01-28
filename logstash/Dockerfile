ARG ELK_VERSION

# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}
ADD mssql-jdbc-7.4.1.jre11.jar /usr/share/logstash/logstash-core/lib/jars/mssql-jdbc-7.4.1.jre11.jar

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
