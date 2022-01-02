## DEPLOYING APPLICATIONS INTO KUBERNETES CLUSTER

In this project, you will build upon your knowledge of Kubernetes architecture, and begin to deploy applications on a K8s cluster. Kubernetes has a lot of moving parts; it operates with several layers of abstraction between your application and host machines where it runs. So many terms, and capabilities that is not realistic to learn it all at once. Hence, you will be introduced to as many concepts as possible, but gradually.

Within this project we are going to learn and see in action following:

1. Deployment of software applications using YAML manifest files with following K8s objects:
- Pods
- ReplicaSets
- Deployments
- StatefulSets
- Services (ClusterIP, NodeIP, Loadbalancer)
- Configmaps
- Volumes
- PersistentVolumes
- PersistentVolumeClaims…and many more

2. Difference between stateful and stateless applications. Deploy MySQL as a StatefulSet and explain why
Limitations of using manifests directly to deploy on K8s

3. Working with Helm templates, its components and the most important parts – semantic versioning
Converting all the .yaml templates into a helm chart

4. Deploying more tools with Helm charts on AWS Elastic Kubernetes Service (EKS)

- Jenkins
- MySQL
- Ingress Controllers (Nginx)
- Cert-Manager
- Ingress for Jenkins
- Ingress for the actual application

5. Deploy Monitoring Tools
- Prometheus
- Grafana

6. Hybrid CI/CD by combining different tools such as: Gitlab CICD, Jenkins. And, you will also be introduced to concepts around GitOps using Weaveworks Flux.

