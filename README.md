# kubernetes-bluegreen-deployment



### Kubernetes Blue-Green Deployment Strategy

**Technologies:** Kubernetes, Docker, YAML, Nginx, kubectl, Git, GitHub.

- Implemented a Blue-Green deployment strategy using Kubernetes Deployments to manage application versions and enable controlled releases.
- Configured separate Blue and Green deployments with three replicas each to maintain application availability during version transitions.
- Created Kubernetes YAML manifests to define deployments, container images, labels, selectors, and replica configurations.
- Configured a NodePort service to expose the application externally and route traffic to the appropriate application pods.
- Practiced application version switching and rollback by managing deployment versions, reducing deployment downtime and release risks.
- Validated deployment health and application availability using kubectl commands and Kubernetes resource monitoring.
