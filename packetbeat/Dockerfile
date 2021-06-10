ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/beats/packetbeat:${ELK_VERSION}

USER root
RUN chown $USER:$USER /usr/share/packetbeat/packetbeat.yml
RUN chmod go-w /usr/share/packetbeat/packetbeat.yml
# RUN ./packetbeat setup --dashboards
# Add your kibana plugins setup here
# Example: RUN kibana-plugin install <name|url>
