*This is the fourteen issue of The Starlet List. If you want to prompt your open source project on star-history.com for free, please check out our [announcement](/blog/list-your-open-source-project).*

---

# VictoriaMetrics is a fast, cost-effective and scalable monitoring solution and time series database

[VictoriaMetrics](https://victoriametrics.com/) is a fast and scalable open source time series database and monitoring solution that lets users build a monitoring platform without scalability issues and minimal operational burden.

## Why use VictoriaMetrics?

VcitoriaMetrics provides users and organizations with better visibility into the health of their systems, helping them identify issues before they become major problems.

- Perfect for collecting metrics (via push and pull models) as well as running queries and generating alerts
- Compatible with Prometheus, Grafana, and accepts metrics in InfluxDB, Graphite, OpenTSDB, OpenTelemetry CSV protocols
- Suitable for running in Kubernetes, Docker or bare metal

VictoriaMetrics lets users:
- Build a monitoring platform without operational burden or scalability issues
- Store millions of data points per second on a single instance
- Scale to a high-load monitoring system across multiple data centers
- Store up to 10x more data using the same compute and storage resources as existing solutions.

Today, VictoriaMetrics products is [one of the most loved monitoring solutions](https://docs.victoriametrics.com/CaseStudies.html) by developers and [10k+ stars on GitHub](https://github.com/VictoriaMetrics/VictoriaMetrics).

## Features

- Highest Ingestion Rates
- Fastest Query Performance
- Smallest Disk Storage Size
- Lowest Memory Usage
- Long-term Storage for Metrics
- Highly Scalable
- Cloud Ready
- Simple Set-up & Operation

VictoriaMetrics is packed with features to help developers, DevOps/SRE engineers to work at peak efficiency.

- **High availability:** VictoriaMetrics Cluster is perfectly suited for building [high availability](https://docs.victoriametrics.com/Cluster-VictoriaMetrics.html#high-availability), [scalability](https://docs.victoriametrics.com/Cluster-VictoriaMetrics.html#cluster-resizing-and-scalability) and [multi-regional setups](https://docs.victoriametrics.com/guides/multi-regional-setup-dedicated-regions.html).
- **Multi-tenancy:** VictoriaMetrics Cluster supports [multiple isolated tenants](https://docs.victoriametrics.com/Cluster-VictoriaMetrics.html#multitenancy) (aka namespaces). Tenants are identified by `accountID` or `accountID:projectID`, which are put inside request [urls](https://docs.victoriametrics.com/Cluster-VictoriaMetrics.html#url-format).
- **Alerting support:** mechanism of alerting and recording rules execution is placed in a separate [vmalert](https://docs.victoriametrics.com/vmalert.html) component, which can be used with any compatible Prometheus HTTP API. For sending alerting notifications vmalert relies on Alertmanager as well as Prometheus does. Vmalert is heavily inspired by Prometheus implementation and aims to be compatible with its syntax.
- **Cross-platform:** VictoriaMetrics can be used on [any popular operating system](https://docs.victoriametrics.com/BestPractices.html#operating-system) like GNU Linux, MacOS, Windows, FreeBSD/OpenBSD and Solaris/SmartOS as well as different [arhitectures](https://docs.victoriametrics.com/BestPractices.html#supported-architectures).
- **Inspections:** VictoriaMetrics Single and Cluster has integrated [vmui](https://docs.victoriametrics.com/Single-server-VictoriaMetrics.html#vmui) which support [query tracing](https://docs.victoriametrics.com/#query-tracing) feature to help you debug your requests and correct them when you make minor mistakes when configuring [MetricsQL](https://docs.victoriametrics.com/MetricsQL.html) queries.

> _We highly recommend you take a look at the [**VictoriaMetrics Documentation**](https://docs.victoriametrics.com/) to learn more about the app._

## Open Source

VictoriaMetrics is one of the most popular open-source software for observability and the community has been their backbone from day one. Thanks to our community we’ve reached over10,000+ stars on GitHuband celebrated [5 Year Anniversary](https://victoriametrics.com/blog/5-year-anniversary-celebrations/)!

VictoriaMetrics team always pay extra attention to performance reports from users and do everything we can to make VictoriaMetrics even better. All the performance improvements we publish are based on real world scenarios, which we learn from and optimize all together with our users.

That is, probably, the main reason why VictoriaMetrics remains on the high level of (cost-)efficiency.

### Star History

[![Star History Chart](https://api.star-history.com/svg?repos=VictoriaMetrics/VictoriaMetrics&type=Date)](https://star-history.com/#VictoriaMetrics/VictoriaMetrics&Date)