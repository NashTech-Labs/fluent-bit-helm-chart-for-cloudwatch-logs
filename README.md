# Fluent Bit Helm Chart

This Helm chart deploys Fluent Bit, a lightweight and flexible log processor and forwarder, to your Kubernetes cluster. Fluent Bit is designed to collect, parse, and forward logs from various sources, including container logs, to different destinations. Using this chart you can send your logs directly to cloudwatch logs.

## Prerequisites

- EKS cluster with Helm installed
- Helm 3.x

## Chart Details

This Helm chart provides a configuration for deploying Fluent Bit as either a DaemonSet or a Deployment within your Kubernetes cluster. You can choose the deployment type using the `kind` parameter in the `values.yaml` file.

### Installing the Chart

To install the Fluent Bit Helm chart, use the following command:

```bash
helm install fluent-bit ./path/to/fluent-bit-chart
