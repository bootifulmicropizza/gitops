# Bootiful Micro Pizza - GitOps

## Introduction

This repo contains an ArgoCD app-of-apps to support GitOps.

## Install

In the root of the repo simply run the following command with kubeconfig configured for the 'devops' environments.

```
kubectl -n argocd apply -k .
```
