## Introduction
Use local disk on one of the node to run nfs server.
Otherwise following:
https://github.com/kubernetes/examples/tree/master/staging/volumes/nfs

## Prerequisite
kubectl create ns nfs
create a local directory on one of the node
manually update 1_storage.yaml to bind the right node
