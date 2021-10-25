# varnish-chart

Helm chart for Varnish Cache

## Install 

### GitLab pages

```bash
helm install --repo https://tebaly.gitlab.io/varnish-chart varnish varnish
```

### OCI
```bash
dependencies:
  - name: varnish
    version: "<version>"
    repository: "oci://registry.gitlab.com/tebaly/varnish-chart"
```