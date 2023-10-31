# varnish-chart

Helm chart for Varnish Cache

## Quick Start

```shell
helm install --repo https://charts.softonic.io my-varnish varnish
```

## Test

```shell
helm template -f values.ci.yaml --namespace test-deleteme test-deleteme . 
```

For more deep testing you can try the chart:

```shell
helm upgrade --install --create-namespace \
  -f values.ci.yaml \
  --namespace test-deleteme \
  test-deleteme . \
  --debug --dry-run
```