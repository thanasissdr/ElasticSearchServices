FROM docker.elastic.co/beats/metricbeat:6.4.0

# COPY metricbeat.yml /usr/metricbeat/metricbeat.yml

USER root
RUN chown root:metricbeat /usr/share/metricbeat/metricbeat.yml
USER metricbeat