---
created: 2022-08-30T03:29:47+05:30
updated: 2022-10-25T01:37:34+05:30
---
[[Kubernetes]]

---
# Local Cluster Setup

## Minikube
- To setup a local K8s cluster, use **Minikube** which is a single node cluster with both master and worker processes installed and a docker runtime. 
- Minikube creates a virtual box on your local machine. The node runs inside that virtual box.
- This can be used for testing.
- Image
	- ![[attachments/Pasted image 20220829175912.png]]

## Installation (Mac)
This will install [[Kubectl]] as well
```
brew install minikube
```

## Spin up a minikube
```
minikube start
```

## Check status
```
minikube status
```