# docling-helm-chart

Deploys Docling CPU-only variant, using torch from the PyTorch CPU index.


## Install
```bash
helm install docling docling-chart --namespace docling --create-namespace
```

### Upgrade
```bash
helm upgrade docling docling-chart
```

## Uninstall
```bash
helm delete docling --namespace docling
```