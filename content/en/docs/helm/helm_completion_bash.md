---
title: "Helm Completion - bash"
---

## helm completion bash

generate autocompletions script for bash

### Synopsis


Generate the autocompletion script for Helm for the bash shell.

To load completions in your current shell session:
$ source <(helm completion bash)

To load completions for every new session, execute once:
Linux:
  $ helm completion bash > /etc/bash_completion.d/helm
MacOS:
  $ helm completion bash > /usr/local/etc/bash_completion.d/helm


```
helm completion bash
```

### Options

```
  -h, --help   help for bash
```

### Options inherited from parent commands

```
      --debug                       enable verbose output
      --kube-apiserver string       the address and the port for the Kubernetes API server
      --kube-as-group stringArray   Group to impersonate for the operation, this flag can be repeated to specify multiple groups.
      --kube-as-user string         Username to impersonate for the operation
      --kube-context string         name of the kubeconfig context to use
      --kube-token string           bearer token used for authentication
      --kubeconfig string           path to the kubeconfig file
  -n, --namespace string            namespace scope for this request
      --registry-config string      path to the registry config file (default "~/.config/helm/registry.json")
      --repository-cache string     path to the file containing cached repository indexes (default "~/.cache/helm/repository")
      --repository-config string    path to the file containing repository names and URLs (default "~/.config/helm/repositories.yaml")
```

### SEE ALSO

* [helm completion](helm_completion.md)	 - generate autocompletions script for the specified shell

###### Auto generated by spf13/cobra on 29-Oct-2020
