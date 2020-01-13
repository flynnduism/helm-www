---
title: "Helm Get Manifest"
weight: 12
---

## helm get manifest

download the manifest for a named release

### Synopsis



This command fetches the generated manifest for a given release.

A manifest is a YAML-encoded representation of the Kubernetes resources that
were generated from this release's chart(s). If a chart is dependent on other
charts, those resources will also be included in the manifest.


```
helm get manifest [flags] RELEASE_NAME
```

### Options

```
      --revision int32       get the named release with revision
      --tls                  enable TLS for request
      --tls-ca-cert string   path to TLS CA certificate file (default "$HELM_HOME/ca.pem")
      --tls-cert string      path to TLS certificate file (default "$HELM_HOME/cert.pem")
      --tls-key string       path to TLS key file (default "$HELM_HOME/key.pem")
      --tls-verify           enable TLS for request and verify remote
```

### Options inherited from parent commands

```
      --debug                     enable verbose output
      --home string               location of your Helm config. Overrides $HELM_HOME (default "/Users/roflynnc/.helm")
      --host string               address of Tiller. Overrides $HELM_HOST
      --kube-context string       name of the kubeconfig context to use
      --tiller-namespace string   namespace of Tiller (default "kube-system")
```

### SEE ALSO
* [helm get](helm_get.md)	 - download a named release

###### Auto generated by spf13/cobra on 13-Jan-2020