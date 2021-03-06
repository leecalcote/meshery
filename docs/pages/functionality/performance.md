---
layout: page
title: Performance Management
permalink: functionality/performance-management
type: functionality
---

# Performance Management
Key to the efficient operation of any service mesh is the measurement and management of it's performance. 

## Load Generators
Meshery provides users with choice of which load generator they prefer to use for a given performance test. Users may set their configure based on their own preference of load generator different from that of the default load generator.

Meshery supports the following load generators and is [extendible](extensibility) to support others:

- Fortio
- wrk2
- NightHawk

### Fortio

Fortio is a fast, small (3Mb docker image, minimal dependencies), 
reusable, embeddable go library as well as a command line tool and server process, 
the server includes a simple web UI and graphical representation of the results 
(both a single latency graph and a multiple results comparative min, max, avg, qps and percentiles graphs).

### wrk2

It is a modern HTTP benchmarking tool capable of generating significant load when run on a single multi-core CPU. It combines a multithreaded design with scalable event notification systems such as epoll and kqueue.

### NightHawk

NightHawk is an L7 (HTTP/HTTPS/HTTP2) performance characterization tool. It currently offers:

- A load testing client which supports HTTP/1.1 and HTTP/2 over HTTP and HTTPS. (HTTPS certificates are not yet validated).
- A simple test server which is capable of generating dynamic response sizes, as well as inject delays.
- A binary to transform nighthawk output to well-known formats, allowing integration with other systems and dashboards.

## Node and Service Mesh Metrics

Meshery provides performance test results alongside environment metrics, including service mesh control and data plane metrics as well as cluster node resource metrics, so that operators may easily understand the overhead of their service mesh's control plane and data plane in context of the overhead incurred on nodes within the cluster.

## Grafana and Meshery

Connect Meshery to your existing Grafana instance and Meshery will import the boards of your choosing. 

<a href="/docs/assets/img/performance-management/meshery-and-grafana.png">
    <img src="/docs/assets/img/performance-management/meshery-and-grafana.png" style="width: 100%" />
</a>

### Connecting to Grafana
If you have an API key configured to restrict access to your Grafana boards, you will need to enter the API key when establishing Meshery's connection to Grafana.

* Importing Grafana boards
    - Importing existing Grafana boards via API
    - Importing custom Grafana board via yaml
* Configuring graph panel preferences

## Prometheus and Meshery
Meshery allows users to connect to one or more Prometheus instances in order to gather telemetric data (in the form of metrics). These metrics may pertain to service meshes, Kubernetes, applications on the mesh or really... any metric that Prometheus has collected.

Once you have connected Meshery to your Prometheus deployment(s), you may perform ad-hoc connectivity tests to verify communication between Meshery and Prometheus.

## Suggested Reading

- Guide: [Interpreting Performance Test Results](/docs/guides/interpreting-performance-test-results)
