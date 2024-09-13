# Awesome Monitoring

A curated list of amazingly awesome tools, services and other shiny things for monitoring and analyze everything.

## Servers

Complex infrastructure software

- [Zabbix](http://www.zabbix.com) - Real-time monitoring of millions of metrics collected from tens of thousands of servers, virtual machines and network devices
- [Shinken](http://www.shinken-monitoring.org/) - Another monitoring framework.
- [Nagios](http://www.nagios.org/) - Computer system, network and infrastructure monitoring software application.
- [check_mk](http://mathias-kettner.com/check_mk.html) - Collection of extensions for Nagios.
- [Opsview](https://www.opsview.com/products/opsview-atom) - Based on Nagios 4, Opsview Core is ideal for small IT and test environments.
- [Centreon](http://www.centreon.com) - IT infrastructure and application monitoring for service performance.
- [Naemon](http://www.naemon.org/) - Network monitoring tool based on the Nagios 4 core with performance enhancements and new features.
- [Icinga 2](https://www.icinga.com/) - A Nagios like monitoring system, rewritten and expanded.
- [openITCOCKPIT](https://openitcockpit.io/) - Powerful open-source monitoring tool built upon Naemon or Nagios, featuring seamless integration with Grafana, an array of comprehensive reports, and visualizations.
- [Sematext Cloud](https://sematext.com/) - Infrastructure and log monitoring with service and log auto-discovery.  Basic plan is free.

Dashboards

- [Grafana](https://grafana.com) - The first really good dashboard for displaying metrics.
- [Dash](https://github.com/afaqurk/linux-dash) - A low-overhead monitoring web dashboard for a GNU/Linux machine.
- [Munin](http://munin-monitoring.org/) - Networked resource monitoring tool.
- [Adagios](http://adagios.org/) - Web based Nagios configuration interface.
- [Thruk](http://www.thruk.org/) - Multibackend monitoring web interface with support for Naemon, Nagios, Icinga and Shinken.
- [Uchiwa](https://uchiwa.io) - Simple dashboard for the Sensu monitoring framework.
- [Monit](http://mmonit.com/monit/#home) - Small Open Source utility for managing and monitoring Unix systems.
- [Netdata](https://www.netdata.cloud/agent/) - Troubleshoot slowdowns and anomalies in your infrastructure with thousands of metrics, interactive visualizations, and insightful health alarms.

Uptime

- [BetterUptime](https://betteruptime.com) - Free for 10 monitors, checked every 3 minutes, improved incident management capabilities
- [Freshping](https://www.freshworks.com/website-monitoring) - Free for 50 monitors, checked every 1 minutes, supports websocket monitoring
- [Monitive](http://monitive.com) - Free for 1 service, checked every 10 minutes with unlimited email & twitter alerts
- [Checkly](https://www.checklyhq.com/) - Code-first synthetic monitoring for modern DevOps. Monitor your APIs and apps at a fraction of the price of legacy providers. Powered by a Monitoring as Code workflow and Playwright.
- [UptimeRobot](https://uptimerobot.com) - Free for 50 monitors, checked every 5 minutes
- [UpTime.onl](https://uptime.onl) - Free for 10 URLs, checked every 5 minutes
- [UpTime360](https://uptime360.net) - checked every 5 minutes. Monitor server, website, blacklist, custom services and publish status pages
                                       Get notified instantly on popular notification channels like - Slack, Twitter, Email, SMS (Twillo) and Pushover
- [PingRobot](https://pingrobot.io) - Free for 50 monitors, checked every 5 minutes
- [Nodown](https://nodown.io) - Free for 5 probes, with email monitoring
- [elmah.io](https://elmah.io/features/uptime-monitoring/) - Uptime monitoring combined with application error logging
- [StatusList.app](https://statuslist.app) - Uptime monitoring with debug details and hosted status page in one dashboard
- [Sematext Synthetics](https://sematext.com/synthetic-monitoring) - Website uptime, API, and SSL certificate monitoring.  Includes status pages and scriptable multi-page user transaction monitoring, etc.

## APM
*Application Performance monitoring*

- [NewRelic](https://newrelic.com) - Complex service for both application and infrastructure monitoring
- [DataDog](https://www.datadoghq.com) - Complex service for both application and infrastructure monitoring
- [OverOps](https://www.overops.com) - OverOps provides Automated Root Cause (ARC) analysis to reduce the time to identify and fix critical production application errors.
- [AppSignal](https://appsignal.com) - Catch errors, track performance, monitor hosts, detect anomalies — all in one tool.

## Web Analytics

- [Matomo](https://matomo.org/) - Take back control with Matomo – a powerful web analytics platform that gives you 100% data ownership.
- [Heap Analytics](https://heap.io/) - Easy event tracking without coding
- [Screpy](https://screpy.com) - Screpy is a web analyzer and monitoring tool. Its powered by Google Lighthouse.
- [Shynet](https://github.com/milesmcc/shynet) - Modern, privacy-friendly, and cookie-free web analytics.

## Bug Tracking

- [Honeybadger](https://www.honeybadger.io) - Monitor application errors, performance, uptime, and logs in one simple tool for developers.
- [Sentry](https://sentry.io) - Application monitoring, event logging and aggregation.
- [Bugsnag](https://bugsnag.com) - Application monitoring, event logging and aggregation.

## Anomalies

- [Banshee](https://github.com/facesea/banshee) - Real-time anomalies(outliers) detection system for periodic metrics

## Logging

- [Brubeck](https://github.com/github/brubeck) - Statsd-compatible stats aggregator written in C
- [Loggly](https://loggly.com) - Aggregate & analyze logs from any source
- [Logit.io](https://logit.io) - Centralise logs and metrics using the ELK Stack, Grafana & Open Distro.
- [Sematext Logs](https://sematext.com/logsene) - Log monitoring with log auto-discovery and alerting; comes with out of the box dashboards, pipelines for transforming, masking, dropping, sampling log events and more.  Basic plan is free.

## Alerting

- [Moira](https://github.com/moira-alert) - Most powerful alerting system, backed by Graphite.
- [Alerta](https://github.com/guardian/alerta) - Distributed, scaleable and flexible monitoring system.
- [Flapjack](http://flapjack.io/) - Monitoring notification routing & event processing system.
- [Seyren](https://github.com/scobal/seyren) - An alerting dashboard for Graphite.

## Database

Tools for databases

- [Anemometer](https://github.com/box/Anemometer) - MySQL Slow Query Monitor

Databases

- [Graphite](https://graphiteapp.org) - More, than a time series database. And so awesome using with Grafana.
- [Prometheus](https://prometheus.io) - Time series database for real-time monitoring and alerting
- [InfluxDB](https://github.com/influxdata/influxdb) - Time-series database built from the ground up to handle high write and query loads
- [Levitate](https://last9.io/levitate-tsdb) - A Managed Time Series Metrics and Events Warehouse built to handle High Cardinality data.
 
## Network

- [Cacti](http://www.cacti.net) - Web-based network monitoring and graphing tool.
- [Observium](http://www.observium.org/) - SNMP monitoring for servers and networking devices. Runs on linux.
- [LibreNMS](https://github.com/librenms/librenms/) - Fork of Observium.
- [Fluere](https://github.com/SkuldNorniern/fluere) - Versatile network interface monitoring and analysis tool, capable of capturing network packets in pcap format, NetFlow data. supports lua based plugins

# License

[![CC4](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
