---
created: 2022-08-28T20:42:44+05:30
updated: 2022-10-25T01:37:34+05:30
---
[[Kubernetes]]

---
# Data Storage
- Any local or remote storage must be thought of as a hard drive plugged into the K8 cluster. K8 does not manage any data persistence. So, the system admin is responsible for backing up the data storage and managing it.
- Working with stateful pods is difficult. So, it is a common practice to host databases outside the K8 cluster and use K8 only for stateless applications.