FROM grafana/grafana:8.5.4

COPY Grafana-DMARC_Reports.json /var/lib/grafana/dashboards/

RUN chmod 644 /etc/grafana/provisioning

COPY grafana-provisioning/ /etc/grafana/provisioning/
