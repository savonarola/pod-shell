# Pod Shell

Utility for interactive selection of a Kubernetes pod and container to run shell in.

# Usage

![Usage](doc/usage.gif)

If a pod has more than one container, one will be prompted to select it too.

# Installation

Copy `pod-shell` to your `$PATH`.

Alternatively, install as a Krew plugin with

```bask
kubectl krew install --manifest-url https://raw.githubusercontent.com/savonarola/pod-shell/master/pod-shell.yaml

kubectl psh
```

# License

Apache 2.0
