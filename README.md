# flux
This flux repo automates the deployment of containers

```text
Note-to-self: Bootstrap may fail, ensure that egress traffic is reachable from within the cluster.
```

# https://fluxcd.io/flux/installation/#github-and-github-enterprise

flux bootstrap github \
  --owner=Joshua-CICD \
  --repository=flux \
  --path=clusters/dev \
  --private=false 
