# test kustomize support argo-rollouts crd


```bash

kustomize build overlays/dev
Error: resource with name rollout-canary does not match a config with the following GVK [~G_~V_Deployment ~G_~V_StatefulSet ~G_~V_ReplicaSet ~G_~V_ReplicationController]
```
