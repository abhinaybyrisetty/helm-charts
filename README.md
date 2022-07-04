# Spinnaker Chart

[Spinnaker](http://spinnaker.io/) is an open source, multi-cloud continuous delivery platform.

## Chart Details
This chart will provision a fully functional and fully featured Spinnaker installation
that can deploy and manage applications in the cluster that it is deployed to.

After stable helm repo was deprecated, Spinnaker helm repo is not maintained by community.
Just hosting this repo for the benefit of the community. Please open a PR if you see any
scope for improvements/corrections

Redis and Minio are used as the stores for Spinnaker state.

For more information on Spinnaker and its capabilities, see it's [documentation](http://www.spinnaker.io/docs).

## Installing the Chart

To install the chart with the release name `my-release`:

```bash
$ helm repo add spinnaker https://abhinaybyrisetty.github.io/helm-charts/
$ helm install --name my-release spinnaker/spinnaker --timeout 600
```

