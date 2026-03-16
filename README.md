# Welcome to the vCluster Workshop at KubeCon EU 2026!

Welcome to the repository for the workshop.

In this workshop you will learn:

- How to run a vCluster platform and vClusters in Docker (vCluster-in-Docker) on your local machine
- How to set up a production-ready platform based on the kubara frameworks general distro
- How GitOps works with Argo CD using a Hub-and-Spoke topology
- How to build a catalog based on Helm umbrella charts
- How GitOps at scale works and how to manage a fleet of clusters and deploy tools across 1, 10, or 100 clusters using label-based deployments

Everything runs on your local machine, so you can stop, pause, and continue at any time.

You will also learn:

- How to collaborate by giving colleagues access to your vClusters or a dedicated vCluster
- How to extend your local environment with external nodes
- How to run GPU workloads on added GPU nodes (simple VMs) and why this matters beyond local development
- How to deploy Ollama (local LLM), kagent, and the Ollama GPU operator by changing only a few labels

This setup is not only for this workshop.
It also shows how different Kubernetes use cases can work in a local lab environment.

You can easily move the same setup to a production Kubernetes cluster in your own environment or cloud provider.

This workshop is not just for today, but also for your future setup.

You will find the following icons as indicators in the documentation:

- 💻 == Hands-on step you can complete yourself
- 👩‍🏫 == Instructor part, because it requires additional resources (e.g. GPU node)
- 💻👩‍🏫 == Instructor-led part, but you can also follow hands-on if you have access to the required resources (e.g. a Kubernetes cluster reachable from your machine)

⚠️ Before the workshop starts, please go through the [Prerequisites](00_PREREQUISITES.md) and [Bootstrapping](01_BOOTSTRAPPING.md) steps to ensure a smooth experience during the session.