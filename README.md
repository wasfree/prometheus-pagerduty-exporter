# Prometheus Pagerduty Exporter Helm Chart

A Prometheus exporter for [PagerDuty](https://www.pagerduty.com/) metrics.

This chart bootstraps a PagerDuty Exporter deployment on a Kubernetes cluster using the Helm package manager.

## Get Repo Info

```console
helm repo add wasfree https://wasfree.github.io/prometheus-pagerduty-exporter
helm repo update
```

_See [helm repo](https://helm.sh/docs/helm/helm_repo/) for command documentation._

## Install Chart

```console
helm install [RELEASE_NAME] wasfree/prometheus-pagerduty-exporter [flags]
```

_See [configuration](#configuration) below._

_See [helm install](https://helm.sh/docs/helm/helm_install/) for command documentation._

## Uninstall Chart

```console
helm uninstall [RELEASE_NAME]
```

This removes all the Kubernetes components associated with the chart and deletes the release.

_See [helm uninstall](https://helm.sh/docs/helm/helm_uninstall/) for command documentation._

## Upgrading Chart

```console
helm upgrade [RELEASE_NAME] wasfree/prometheus-pagerduty-exporter [flags]
```

_See [helm upgrade](https://helm.sh/docs/helm/helm_upgrade/) for command documentation._

## Configuration

See [Customizing the Chart Before Installing](https://helm.sh/docs/intro/using_helm/#customizing-the-chart-before-installing). To see all configurable options with detailed comments:

```console
helm show values wasfree/prometheus-pagerduty-exporter
```

You may also run `helm show values` on this chart's [dependencies](#dependencies) for additional options.
