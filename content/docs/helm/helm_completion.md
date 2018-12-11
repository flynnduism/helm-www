## helm completion

Generate autocompletions script for the specified shell (bash or zsh)

### Synopsis


Generate autocompletions script for Helm for the specified shell (bash or zsh).

This command can generate shell autocompletions. e.g.

	$ helm completion bash

Can be sourced as such

	$ source <(helm completion bash)


```
helm completion SHELL [flags]
```

### Options

```
  -h, --help   help for completion
```

### Options inherited from parent commands

```
      --debug                           enable verbose output
      --home string                     location of your Helm config. Overrides $HELM_HOME (default "~/.helm")
      --host string                     address of Tiller. Overrides $HELM_HOST
      --kube-context string             name of the kubeconfig context to use
      --kubeconfig string               absolute path to the kubeconfig file to use
      --tiller-connection-timeout int   the duration (in seconds) Helm will wait to establish a connection to tiller (default 300)
      --tiller-namespace string         namespace of Tiller (default "kube-system")
```

### SEE ALSO

* [helm](../../helm/#helm)	 - The Helm package manager for Kubernetes.

###### Auto generated by spf13/cobra on 1-Aug-2018