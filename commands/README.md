# Kubectl and other useful commands

## Introduction
This is just to have a reference of commands tried out during learning and is not inclusive. 

Official documentation : [kubectl-commands](https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands)

### commands

Leave out header in the output of any kubectl commands, add --no-header. This could be useful to count the lines of output (in order to count number of pods etc.)
`kubectl get pods -n elk --no-header`

To refer the fields while authoring a manifest file for _Job_. 
`kubectl describe job.spec --recursive` 
