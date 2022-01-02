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

## Choosing the right Kubernetes cluster set up
When it comes to using a Kubernetes cluster, there is a number of options available depending on the ultimate use of it. For example, if you just need a cluster for development or learning, you can use lightweight tools like Minikube, or k3s. These tools can run on your workstation without heavy system requirements. Obviously, there is limit to the amount of workload you can deploy there for testing purposes, but it works exactly like any other Kubernetes cluster.

On the other hand, if you need something more robust, suitable for a production workload and with more advanced capabilities such as horizontal scaling of the worker nodes, then you can consider building own Kubernetes cluster from scratch just as you did in Project 21. If you have been able to automate the entire bootstrap using Ansible, you can easily spin up your nodes with Terraform, and configure the cluster with your Ansible configuration scripts.

It it a great combination of tools responsible for different parts of your applications:

- Terraform for infrastructure provisioning
- Ansible for cluster master and worker nodes configuration
- Kubernetes for deploying your containerized application and orchestrating the deployment

Other options will be to leverage a Managed Service Kubernetes cluster from public cloud providers such as: AWS EKS, Microsoft AKS, or Google Cloud Platform GKE. There are so many more options out there. Regardless of whichever one you choose, the experience is usually very similar.

Most organisations choose Managed Service options for obvious reasons such as:

- Less administrative overheads
- Reduced cost of ownership
- Improved Security
- Seamless support
- Periodical updates to a stable and well-tested version
- Faster cluster spin up… and many more



