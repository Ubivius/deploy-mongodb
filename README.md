# Deploy-MongoDB

A database used by the microservices' platform

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

- mongoDB · bitnami/mongodb (https://artifacthub.io/packages/helm/bitnami/mongodb)

Once Helm is set up properly, add the repo as follows:

## Get Repo Info

```console
$ helm repo add bitnami https://charts.bitnami.com/bitnami
$ helm repo update
```

## Installing the Chart

To install the chart with the release name `mongodb`:

```console
$ helm install mongodb --version <version> bitnami/mongodb -f values.yaml
$ kubectl apply -f configmap.yaml
```

## Uninstalling the Chart

To uninstall/delete the mongodb deployment:

```console
$ helm delete mongodb
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
