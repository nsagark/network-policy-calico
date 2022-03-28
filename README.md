# tigera-operator
Calico Network Policy Repo
Calico CNI allows both routing of traffic within Kubernetes and implement the network policy to filter traffic within and in/out of the cluster. This repo provides calico add-on with Nirmata for deployment across different infratructure type - on-prem or cloud provider managed Kubernetes clusters.

For EKS clusters, please use kustomize option to include EKS specific configuration that leverages AWS VPC CNI for traffic routing and Calico for network policy management.
