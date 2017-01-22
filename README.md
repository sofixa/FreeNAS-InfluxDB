# FreeNAS-InfluxDB
A bunch of InfluxDB templates to parse the Graphite output of FreeNAS


To use it, all you have to do is append the contents of [influxdb.conf](./influxdb.conf) to your InfluxDB configuration file (usually in /etc/influxdb/influxdb.conf), and configure your FreeNAS to send statistics over there. Sprinkle on some Grafana goodness (i'll include an example Grafana dashboard to this project ASAP), and enjoy!
