## helm serve

Start a local http web server

### Synopsis


This command starts a local chart repository server that serves charts from a local directory.

The new server will provide HTTP access to a repository. By default, it will
scan all of the charts in '$HELM-HOME/repository/local' and serve those over
the local IPv4 TCP port (default '127.0.0.1:8879').

This command is intended to be used for educational and testing purposes only.
It is best to rely on a dedicated web server or a cloud-hosted solution like
Google Cloud Storage for production use.

See https://github.com/helm/helm/blob/master/docs/developing-charts.md#hosting-chart-repositories
for more information on hosting chart repositories in a production setting.


```
helm serve [flags]
```

### Options

```
      --address string     Address to listen on (default "127.0.0.1:8879")
  -h, --help               help for serve
      --repo-path string   Local directory path from which to serve charts
      --url string         External URL of chart repository
```

### Options inherited from parent commands

```
      --debug                           Enable verbose output
      --home string                     Location of your Helm config. Overrides $HELM-HOME (default "~/.helm")
      --host string                     Address of Tiller. Overrides $HELM-HOST
      --kube-context string             Name of the kubeconfig context to use
      --kubeconfig string               Absolute path of the kubeconfig file to be used
      --tiller-connection-timeout int   The duration (in seconds) Helm will wait to establish a connection to Tiller (default 300)
      --tiller-namespace string         Namespace of Tiller (default "kube-system")
```

### SEE ALSO

* [helm](../../docs/helm/#helm)	 - The Helm package manager for Kubernetes.

###### Auto generated by spf13/cobra on 16-May-2019