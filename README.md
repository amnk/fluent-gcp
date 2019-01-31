# fluent-gcp

fluent-gcp is a Helm chart to install fluent with Stackdriver integration. This might be useful in several cases:

- send logs from one GCP project to another;
- send logs from non-cloud installation to Stackdriver;
- custom fluent installation with some plugins, etc... ;

I originally started working on it to send logs from one GCP project to another, and then saw several open issues:
- https://github.com/GoogleCloudPlatform/fluent-plugin-google-cloud/issues/156
- https://github.com/fluent/fluentd-kubernetes-daemonset/issues/8
