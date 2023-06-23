# Deploy the Kubernetes Dashboard (web UI)

You can use Dashboard to deploy containerized applications to a Kubernetes cluster, troubleshoot your containerized application, and manage the cluster resources. You can use Dashboard to get an overview of applications running on your cluster, as well as for creating or modifying individual Kubernetes resources (such as Deployments, Jobs, DaemonSets, etc). For example, you can scale a Deployment, initiate a rolling update, restart a pod or deploy new applications using a deploy wizard.

A service account (k8s-admin) with administrative privileges is created as part of this terraform module.

References:

https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/
