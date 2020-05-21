This is your first step.

## Task

This is an _example_ of creating a scenario and running a **command**

Start the cluster

`minikube start`{{execute}}

Create the directory for `kfctl` repo

`mkdir -p go/src/github.com/kubeflow`{{execute}}

Clone
`cd go/src/github.com/kubeflow && git clone https://github.com/kubeflow/kfctl.git && cd kfctl`{{execute}}

Build `kfctl` CLI

`make build`{{execute}}
