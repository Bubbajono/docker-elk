ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

# Install JDBC to be able to connect to SQL Server
COPY mssql-jdbc-9.4.0.jre8.jar /usr/share/logstash/logstash-core/lib/jars/mssql-jdbc-9.4.0.jre8.jar