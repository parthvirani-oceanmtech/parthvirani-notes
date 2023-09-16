---
created: 2022-09-05T08:55:44+05:30
updated: 2022-10-25T01:37:34+05:30
---
[[Kubernetes]]

---
# Helm Package Manager
- It serves 2 purposes
	- **Package manager for K8s**
		- Used to package YAML files and distribute them in public & private repositories
	- **Templating Engine**
		- Used to define a template YAML with placeholders for dynamic values
		- Useful in CI/CD
		- ![[attachments/Pasted image 20220904233635.png]]
- Uses
	- Deploy same application across multiple clusters
		- Package the application as a Helm chart and deploy it across multiple clusters

## Helm Charts
- Bundle of YAML files
- Example: If you need to implement elastic search in your application, instead of creating the YAML files for all the components, you can use an existing helm chart from **Helm Repository**.
- You can also create and push your own helm charts for others to use.
- Image
	- ![[attachments/Pasted image 20220904232830.png]]

#### Helm Chart Directory Structure
- `values.yaml` contains default values for the placeholders
![[attachments/Pasted image 20220904234111.png]]

## Helm Commands
Install a packaged app from the Helm Chart
```
helm install --values=my-values.yaml <chartname>
```

![[attachments/Pasted image 20220904234614.png]]