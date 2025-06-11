# Helm Chart Repository

## Package and Update Helm Chart

Run these commands to package your chart and update the repository index:

```bash
helm package .
helm repo index . --url https://umarfd.github.io/umarfd-helm-chart/