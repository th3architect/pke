## pke install worker pipeline-ready

Register node as ready at Pipeline

### Synopsis

Register node as ready at Pipeline

```
pke install worker pipeline-ready [flags]
```

### Options

```
  -h, --help                                    help for pipeline-ready
      --kubernetes-infrastructure-cidr string   network CIDR for the actual machine (default "192.168.64.0/20")
      --pipeline-cluster-id int32               Cluster ID to use with Pipeline API
      --pipeline-nodepool string                name of the nodepool the node belongs to
      --pipeline-org-id int32                   Organization ID to use with Pipeline API
  -t, --pipeline-token string                   Token for accessing Pipeline API
  -u, --pipeline-url string                     Pipeline API server url
```

### SEE ALSO

* [pke install worker](pke_install_worker.md)	 - Installs Banzai Cloud Pipeline Kubernetes Engine (PKE) Worker node

