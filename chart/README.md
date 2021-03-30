# MongoDB Helm Chart

- mongoDB · bitnami/mongodb (https://artifacthub.io/packages/helm/bitnami/mongodb)

## Get Repo Info

```console
$ helm repo add bitnami https://charts.bitnami.com/bitnami
$ helm repo update
```

## Installing the Chart

To install the chart with the release name `mongodb`:

```console
$ helm install mongodb --version <version> bitnami/mongodb -f values.yaml
```

## Uninstalling the Chart

To uninstall/delete the mongodb deployment:

```console
$ helm delete mongodb
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
