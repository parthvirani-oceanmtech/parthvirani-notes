---
created: 2022-08-28T19:38:54+05:30
updated: 2022-10-25T01:37:37+05:30
---
[[Kubernetes]]

---
# Intro

- [[Kubernetes]] is an open-source **container orchestration** tool developed by Google
- It helps us manage containerized applications in different deployment environments

## Container Orchestration
- Containers act as perfect hosts for micro-services (running independently)
- The rise of micro-services architecture led to applications using 1000s of containers that need to be smartly managed.
- Container orchestration offers:
	- High Availability (no downtime)
	- Scalability
	- Disaster Recovery 
- Example
	- In the image below, a replica of both Application [[Components#Pod|Pod]] and the DB Pod are maintained on a separate node with load balancing. So, even if one of the nodes fail, the application will be accessible.
	- ![[attachments/Pasted image 20220828121643.png]]