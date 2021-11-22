<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  

- [Deploying Turbonomic(server and kube agent) with GitOps](#deploying-turbonomicserver-and-kube-agent-with-gitops)
  - [Prerequisite for deploying Turbonomic to OpenShift Cluster](#prerequisite-for-deploying-turbonomic-to-openshift-cluster)
  - [Deploying Turbonomic with GitOps](#deploying-turbonomic-with-gitops)
  - [Verify Deployment with GitOps](#verify-deployment-with-gitops)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Deploying Turbonomic(server and kube agent) with GitOps

## Prerequisite for deploying Turbonomic to OpenShift Cluster
- OpenShift 4.6+
- Argocd
- Resource requirement, please refer to the [Turbonomic Installation Guide](https://docs.turbonomic.com/docApp/doc/index.html?config=Install_Pnt#!/Latest_Install/_INSTALL_Topics_XL/TOPIC_Minimum_Requirements_XL.xml).

## Deploying Turbonomic with GitOps 
- Deploy Turbonomic(server)
  - [Deploy Turbonomic(server) via GUI console](docs/Gitops-Turbonomic-Install.md#deploying-turbonomicserver-with-gitops-via-gui-console)
  - [Deploy Turbonomic(server) via CLI](docs/Gitops-Turbonomic-Install.md#deploying-turbonomic-with-gitops-cli) 
- Deploy Kubeturbo(kube agent)
  - [Deploy kubeturbo(kube agent) via GUI console](docs/Gitops-kubeturbo-Install.md#deploying-kubeturbokube-agent-with-gitops-via-gui-console) 
  - [Deploy kubeturbo(kube agent) via CLI](docs/Gitops-kubeturbo-Install.md#deploying-kubeturbokube-agent-with-gitops-cli) 

## Verify Deployment with GitOps
- Verify Deployment
  - [Verify Deployment via GUI](docs/Gitops-verify-deployment.md#verify-deployment-via-gui)
  - [Verify Deployment via CLI](docs/Gitops-verify-deployment.md#verify-deployment-via-cli)
  - [Verify Kubeturbo agent from Turbonomic Console](docs/Gitops-verify-kubeturbo.md)