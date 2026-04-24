# Namespace
 A Namespace is a way to logically divide a cluster into mutiple virtual cluster
 Same cluster ✅
Separate environments/resources ✅
A namespace is used to organize, isolate, and manage resources within a Kubernetes cluster.
Avoid naming conflicts
Separate environments (dev/test/prod)
Apply RBAC (access control)
Resource limits per team
Better organization



# pod

A pod is the smallest and simplest unit in Kubernetes that you can deploy.
A pod is a group of one or more containers that:

Share network (same IP)
Share storage (volumes)
Run together on the same node
Pods are ephemeral (temporary)
If a pod dies → Kubernetes creates a new one (via Deployment)
Talk via localhost
