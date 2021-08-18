# Harvester CSI Driver Helm Chart

[Harvester CSI Driver](https://github.com/harvester/harvester-csi-driver) provides a CSI interface used by guest kubernetes clusters in Harvester. It connects to the host cluster and hot-plug host volumes to the VMs to provide native storage performance.

Introduction
------------

This chart helps to install the harvester csi driver on the guest Kubernetes cluster in Harvester using the [Helm](https://helm.sh) package manager.

## Installing the Chart

To install the chart with the release name `my-release`:

```console
helm repo add harvester https://charts.harvesterhci.io
helm repo update
helm install -n $namespace my-release harvester/harvester-csi-driver
```

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```console
helm uninstall -n $namespace my-release
```
