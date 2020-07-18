# LocalStack Helm Chart for Kubernetes deployment

## Credits

1. [LocalStack - A fully functional local AWS cloud stack](https://github.com/localstack/localstack)
2. [everpeace own work on Helm chart](https://github.com/everpeace/helm-charts/tree/master/localstack)

## Install

1. Override any necessary `values.yaml` settings.

2. Create release.

```bash
helm package .
helm install localstack ./localstack-helm-x.tgz
```

3. Connect to localstack.
