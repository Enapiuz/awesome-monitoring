# Awesome Monitoring

A curated list of amazingly awesome tools, services and other shiny things for monitoring and analyze everything.

## Servers

Complex infrastructure software

- [Zabbix](http://www.zabbix.com) - Real-time monitoring of millions of metrics collected from tens of thousands of servers, virtual machines and network devices
- [Nagios](http://www.nagios.org/) - Computer system, network and infrastructure monitoring software application.
- [check_mk](http://mathias-kettner.com/check_mk.html) - Collection of extensions for Nagios.
- [Opsview](https://www.opsview.com/products/opsview-atom) - Based on Nagios 4, Opsview Core is ideal for small IT and test environments.
- [Centreon](http://www.centreon.com) - IT infrastructure and application monitoring for service performance.
- [Naemon](http://www.naemon.org/) - Network monitoring tool based on the Nagios 4 core with performance enhancements and new features.
- [Icinga 2](https://www.icinga.com/) - A Nagios like monitoring system, rewritten and expanded.
- [openITCOCKPIT](https://openitcockpit.io/) - Powerful open-source monitoring tool built upon Naemon or Nagios, featuring seamless integration with Grafana, an array of comprehensive reports, and visualizations.
- [Sematext Cloud](https://sematext.com/) - Infrastructure and log monitoring with service and log auto-discovery.  Basic plan is free.
- [Middleware](https://middleware.io/) - Full-stack observability platform with infrastructure monitoring, Kubernetes monitoring, APM, logs, distributed tracing, real user monitoring, synthetic monitoring, and AI-assisted incident investigation.
- [Fivenines](https://fivenines.io) - Server, uptime, cron and network monitoring. One platform. 5 first monitors are free.

Dashboards

- [Grafana](https://grafana.com) - The first really good dashboard for displaying metrics.
- [Dash](https://github.com/afaqurk/linux-dash) - A low-overhead monitoring web dashboard for a GNU/Linux machine.
- [Munin](http://munin-monitoring.org/) - Networked resource monitoring tool.
- [Adagios](http://adagios.org/) - Web based Nagios configuration interface.
- [Thruk](http://www.thruk.org/) - Multibackend monitoring web interface with support for Naemon, Nagios, and Icinga.
- [Uchiwa](https://uchiwa.io) - Simple dashboard for the Sensu monitoring framework.
- [Monit](http://mmonit.com/monit/#home) - Small Open Source utility for managing and monitoring Unix systems.
- [Netdata](https://www.netdata.cloud/agent/) - Troubleshoot slowdowns and anomalies in your infrastructure with thousands of metrics, interactive visualizations, and insightful health alarms.
- [HomeLab Monitor](https://github.com/SikamikanikoBG/homelab-monitor) - Self-hosted homelab dashboard in a single Docker container - per-container GPU/VRAM attribution, Docker health, systemd service status, and host vitals across multiple machines over SSH.
- [KubeStellar Console](https://github.com/kubestellar/console) - Multi-cluster Kubernetes monitoring dashboard with AI-powered operations and real-time observability across edge and cloud clusters.
- [Kula](https://github.com/c0m4r/kula) - Lightweight, self-contained Linux server monitoring tool

Uptime and Synthetic Monitoring

External checks that request your endpoints from outside your own infrastructure

- [Better Stack](https://betterstack.com/uptime) - Uptime monitoring bundled with log management and incident response, with on-call scheduling.
- [BlueWave Uptime](https://github.com/bluewave-labs/bluewave-uptime) - Open-source, self-hosted monitoring tool built with React.js, Node.js, and MongoDB, designed to track server uptime, response times, and incidents in real-time with beautiful visualizations.
- [Freshping](https://www.freshworks.com/website-monitoring) - Free for 50 monitors, checked every 1 minutes, supports websocket monitoring
- [Monitive](http://monitive.com) - Free for 1 service, checked every 10 minutes with unlimited email & twitter alerts
- [Oack](https://oack.io) - HTTP monitoring with TCP kernel telemetry, 6-phase latency breakdown, Server-Timing header capture, Cloudflare CDN enrichment, and built-in incident management with on-call scheduling.
- [Checkly](https://www.checklyhq.com/) - Code-first synthetic monitoring for modern DevOps. Monitor your APIs and apps at a fraction of the price of legacy providers. Powered by a Monitoring as Code workflow and Playwright.
- [Cronitor](https://cronitor.io) - Cron job and heartbeat monitoring alongside uptime checks, with schedule-aware alerting.
- [Pingdom](https://www.pingdom.com) - Synthetic and real user monitoring with transaction checks from 100+ probe locations.
- [Pulsetic](https://pulsetic.com) - Uptime monitoring and status pages, checks run from 15 global locations.
- [Safeship](https://safeship.app) - Endpoint monitoring that validates the JSON body against a schema rather than only the status code, billed per check performed. Configurable from an AI editor over MCP.
- [StatusCake](https://www.statuscake.com) - Uptime, page speed, server and SSL monitoring with Lighthouse data on standard plans.
- [Uptime.com](https://uptime.com) - 30+ check types including transaction monitoring and private location probes, with SLA reporting.
- [UptimeRobot](https://uptimerobot.com) - Free for 50 monitors, checked every 5 minutes
- [UpTime.onl](https://uptime.onl) - Free for 10 URLs, checked every 5 minutes
- [UpTime360](https://uptime360.net) - checked every 5 minutes. Monitor server, website, blacklist, custom services and publish status pages
                                       Get notified instantly on popular notification channels like - Slack, Twitter, Email, SMS (Twillo) and Pushover
- [Kapient](https://kapient.com) - Website monitoring for small businesses covering uptime, SSL, DNS, email deliverability, security, SEO, ADA compliance, and Google Business Profile, with AI-generated fix instructions tailored to your tech stack.
- [elmah.io](https://elmah.io/features/uptime-monitoring/) - Uptime monitoring combined with application error logging
- [StatusList.app](https://statuslist.app) - Uptime monitoring with debug details and hosted status page in one dashboard
- [ePulz.io](https://epulz.io) - EU-hosted, GDPR-friendly uptime monitoring with public status pages, SSL and domain expiry, heartbeats, visual checks and alerts via email/Telegram/Slack/MS Teams. 14 languages.
- [Sematext Synthetics](https://sematext.com/synthetic-monitoring) - Website uptime, API, and SSL certificate monitoring.  Includes status pages and scriptable multi-page user transaction monitoring, etc.
- [Tianji](https://github.com/msgbyte/tianji) - All-in-One Insight Hub
- [SSL Certificate Monitor](https://github.com/brancogao/ssl-certificate-monitor) - Open-source SSL/TLS certificate expiry monitoring tool with web UI and REST API. Checks certificate validity and days until expiration.
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) - An easy-to-use self-hosted monitoring tool.
- [Phare](https://phare.io/products/uptime) - Free 100k monitoring events per months, 30s intervals, unlimited users, incident management, and sleek status pages.
- [Oh Dear](https://ohdear.app) - Monitoring for uptime, performance, SSL certificates, broken links, and DNS, with hosted status pages
- [DevHelm](https://devhelm.io) - Developer-first uptime monitoring (HTTP, DNS, TCP, ICMP, heartbeat) with dependency intelligence for 80+ providers, hosted status pages, and config-as-code. Free tier: 50 monitors.
- [Uptimeify.io](https://uptimeify.io) - Reliable and simple website and API monitoring with instant alerts and status pages.
- [VisualSentinel](https://visualsentinel.com) - Website monitoring with uptime, visual change detection (screenshot diff of the live site), SSL, DNS, performance, and content checks. Free tier for 3 monitors, checks from EU and US. Alerts via Slack, Discord, WhatsApp, Telegram, PagerDuty and webhooks.
- [Crontiq](https://crontiq.io) - Free cron job monitoring with automatic JSON metric extraction and zero-config anomaly detection. 20 monitors free forever.
- [Spork](https://sporkops.com) - Uptime monitoring with built-in status pages, CLI, and Terraform provider. Multi-region consensus checks from $4/mo.
- [FlareWarden](https://flarewarden.com) — Uptime, content, dependency, and SSL monitoring with multi-region verification and status pages. Free plan includes 15 monitors, 5-minute checks, and 90 days of history.
- [Hyperping](https://hyperping.com) - Uptime, API, cron, and server monitoring from 18 locations, with Playwright browser checks, on-call scheduling, and hosted status pages.
- [UpWatchr](https://upwatchr.io) - Free native Windows desktop app for uptime monitoring of websites and services. Local-first: checks run from your own machine, no cloud and no account.
- [sunwatch](https://sunwatch.sunfamily.xyz) - Crypto-paid uptime monitoring for side projects. Pay per monitor with USDC on Base; webhook alerts on down/up state changes.
- [Drumbeats](https://drumbeats.io) - Cron, heartbeat, and uptime monitoring with incident management and status pages. Free for up to 50 monitors, 200K Beats/mo, 1-minute checks, no credit card. One curl ping to instrument a job, no agent or SDK.
- [Superhighway](https://superhighway.walls.sh) - Web API whose `/scrape` endpoint turns any URL into clean Markdown, useful for building your own content/page-change monitoring (e.g. competitor pricing, changelogs, pages without an RSS feed). See the [change-detection tutorial](https://superhighway.walls.sh/guides/web-change-detection-agent): scrape, SHA-256 hash comparison, LLM-summarize what changed, and schedule with cron or GitHub Actions. Free API key or pay-per-call.

## APM
*Application Performance monitoring*

- [NewRelic](https://newrelic.com) - Complex service for both application and infrastructure monitoring
- [Last9](https://last9.io/) - OpenTelemetry-native observability platform for APM, metrics, logs, and traces, built to handle high-cardinality data at scale.
- [Uptrace](https://uptrace.dev) - OpenTelemetry-native APM. 
- [DataDog](https://www.datadoghq.com) - Complex service for both application and infrastructure monitoring
- [OverOps](https://www.overops.com) - OverOps provides Automated Root Cause (ARC) analysis to reduce the time to identify and fix critical production application errors.
- [AppSignal](https://appsignal.com) - Catch errors, track performance, monitor hosts, detect anomalies — all in one tool.
- [BitDive](https://bitdive.io/) - APM for Java/Kotlin with distributed tracing, method-level profiling, and performance metrics.
- [Middleware](https://middleware.io) - Middleware's APM helps you troubleshoot issues in real-time, optimize performance, improve user experience, and reduce downtime.
- [PerfScope](https://github.com/sattyamjjain/perfscope) - Advanced Python performance profiler with decorator-based setup, call tree visualization, memory tracking, and multi-format report export.
- [Muscula](https://muscula.com/) - Lightweight application monitoring platform for developers with AI-native error reporting and debugging.
- [groundcover](https://www.groundcover.com/) - eBPF-based observability platform for Kubernetes with logs, metrics, traces, and APM; deployed inside the user's own cloud (BYOC).
- [CoreDash](https://coredash.app) - Real user monitoring for Core Web Vitals (LCP, INP, CLS, TTFB, FCP) with element level attribution, request waterfalls, LoAF data, and a built in MCP server so AI agents can query live performance data. EU hosted, GDPR compliant.

## Web Analytics

- [Matomo](https://matomo.org/) - Take back control with Matomo – a powerful web analytics platform that gives you 100% data ownership.
- [Heap Analytics](https://heap.io/) - Easy event tracking without coding
- [Screpy](https://screpy.com) - Screpy is a web analyzer and monitoring tool. Its powered by Google Lighthouse.
- [PageGuard](https://pageguard.org) - Free all-in-one website health scanner powered by Lighthouse. Monitors performance, SEO, accessibility, and best practices with AI-generated action plans and a free REST API.
- [Shynet](https://github.com/milesmcc/shynet) - Modern, privacy-friendly, and cookie-free web analytics.
- [Tianji](https://github.com/msgbyte/tianji) - All-in-One Insight Hub

## API Status Aggregation

- [API Status Check](https://apistatuscheck.com) - Real-time status dashboard aggregating 285 third-party API status pages across 29 categories, including AI platforms (OpenAI, Anthropic), cloud providers (AWS, Vercel), payments (Stripe, PayPal), and developer tools (GitHub, Supabase). Includes embeddable status badges.
- [DownStatus](https://isitdownstatus.com) - Free JSON API providing real-time status for GitHub, AWS, Discord, Cloudflare, Stripe, and 90+ popular services.
- [IncidentHub](https://incidenthub.cloud) - Status page aggregator for monitoring SaaS and cloud providers.
- [OpenChainBench](https://openchainbench.com) - Open live benchmarks of blockchain infrastructure APIs and RPC providers (latency p50/p90/p99, success rate, multi-region), built on a public Prometheus; all data CC-BY-4.0.
- [StatusGator](https://statusgator.com) - Cloud service monitoring, aggregating status pages of cloud services into a single dashboard.
- [Voidly Check](https://github.com/voidly-ai/voidly-check-action) - GitHub Action that verifies your services aren't blocked in target countries (Iran, China, Russia, etc.) using real OONI measurements. Backed by `api.voidly.ai` (19.6M samples).
- [ClaudeDown](https://claudedown.com) - Real-time Claude AI complaint tracker using Twitter/X sentiment data to detect outages before official status pages.

## API Analytics

- [Apitally](https://apitally.io) - Analytics, request logging and monitoring for REST APIs with a focus on simplicity and data privacy.
- [BurnRate](https://getburnrate.io) - AI coding cost analytics CLI that tracks usage and spend across Claude Code, Cursor, Copilot, Windsurf, Aider, Cline, and Codex. Includes optimization rules and rate limit monitoring.
- [ReqKey](https://www.reqkey.com) - API key authentication, usage credits, rate limiting, and request analytics for REST APIs via a single verify call. SDKs for Python, Node.js, Go, Rust, PHP, .NET, and Java, with a free tier of 100,000 requests per month.

## Bug Tracking

- [Honeybadger](https://www.honeybadger.io) - Monitor application errors, performance, uptime, and logs in one simple tool for developers.
- [Sentry](https://sentry.io) - Application monitoring, event logging and aggregation.
- [Bugsnag](https://bugsnag.com) - Application monitoring, event logging and aggregation.

## Anomalies

- [Banshee](https://github.com/facesea/banshee) - Real-time anomalies(outliers) detection system for periodic metrics

## Logging

- [Brubeck](https://github.com/github/brubeck) - Statsd-compatible stats aggregator written in C
- [Loggly](https://loggly.com) - Aggregate & analyze logs from any source
- [Last9](https://last9.io/) - OpenTelemetry-native observability platform with log collection, search, and analysis.
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
- [QuerySharp](https://querysharp.com) - AI-Powered PostgreSQL performance monitoring. Slow query analysis, index recommendations, query rewriting.

Databases

- [Graphite](https://graphiteapp.org) - More, than a time series database. And so awesome using with Grafana.
- [Prometheus](https://prometheus.io) - Time series database for real-time monitoring and alerting
- [InfluxDB](https://github.com/influxdata/influxdb) - Time-series database built from the ground up to handle high write and query loads
- [Levitate](https://last9.io/levitate-tsdb) - A Managed Time Series Metrics and Events Warehouse built to handle High Cardinality data.
 
## Network

- [Cacti](http://www.cacti.net) - Web-based network monitoring and graphing tool.
- [dish](https://github.com/thevxn/dish) -  A lightweight monitoring service that efficiently checks socket connections and can be configured remotely. 
- [NetHawk](https://github.com/Flowtriq/nethawk) - Real-time network traffic analysis TUI built in Go. Features bandwidth monitoring, protocol breakdown, top talkers, and DDoS attack detection.
- [Observium](http://www.observium.org/) - SNMP monitoring for servers and networking devices. Runs on linux.
- [Smokeping](https://oss.oetiker.ch/smokeping/) - SmokePing is a deluxe latency measurement tool.
- [LibreNMS](https://github.com/librenms/librenms/) - Fork of Observium.
- [Fluere](https://github.com/SkuldNorniern/fluere) - Versatile network interface monitoring and analysis tool, capable of capturing network packets in pcap format, NetFlow data. supports lua based plugins
- [Flowtriq](https://github.com/Flowtriq/flowtriq-pfsense-opnsense) - DDoS detection for firewalls and routers (pfSense, OPNsense, VyOS) via NetFlow/sFlow export. Detects volumetric floods, SYN floods, amplification attacks, and provides real-time alerting with automated mitigation.

## Related

- [Awesome Performance Engineering](https://github.com/be-next/awesome-performance-engineering) - Observability and performance testing tools for performance engineering.

# License

[![CC4](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
