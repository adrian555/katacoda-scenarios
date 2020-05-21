This is your first step.

## Task

This is an _example_ of creating a scenario and running a **command**

Start the cluster

`minikube start`{{execute}}

Install `go` 1.13

`cd /usr/local && rm -rf go`{{execute}}
`wget https://dl.google.com/go/go1.13.3.linux-amd64.tar.gz && tar zxvf go1.13.3.linux-amd64.tar.gz`{{execute}}

Create the directory for `kfctl` repo

`cd && mkdir -p go/src/github.com/kubeflow`{{execute}}

Clone
`cd go/src/github.com/kubeflow && git clone https://github.com/kubeflow/kfctl.git && cd kfctl`{{execute}}

Build `kfctl` CLI

`make build`{{execute}}
