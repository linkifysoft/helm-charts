## KAS Chart

1. Package helm chart
```bash
helm package kas-quarkus/ --destination ./packages
```

2. Create index file to publish
``bash
helm repo index --url https://linkifysoft.github.io/helm-charts/ .
```