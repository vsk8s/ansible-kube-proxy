# Kubernetes Proxy

Set up a new kubernetes proxy for a worker node.

A valid kubeconfig is expected to be placed at the path of `kube_proxy_config`.

Configuration is not done how the documentation describes, but with a config
file. See https://github.com/vs-eth/microkube/blob/master/pkg/handlers/kube/KubeProxyConfigHandler.go
for an example

