# k3s-kube-explorer-poc
This a POC about installing the great kube-explorer on k3s or rke2

## Quickstart

To use this poc you first install k3s in the standard way

`curl -sfL https://get.k3s.io | sh - `

After that just clone/download the files of this repo and apply it to your k3s installation.

`k3s kubectl apply -f ke.admin-user.yaml -f ke.admin-user-role.yaml -f ke.deployment.yaml -f ke.service.yaml`
