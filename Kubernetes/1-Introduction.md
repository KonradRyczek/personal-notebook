# Introduction
- Container orchestration - running container loads across servers (nodes)
- Runs on top of docker (usually) as a set of APIs
- Provides API/CLI to manace containers across servers

Orchestration is designed to automate change and monitor the state of things

When choosinng kubernetes usually the github pure upstream isn't used. It's great as a base for learning but lacks the built on top software offered by kubernetes distributions from vendors.

## Kubernetes or Swarm?

### Swarm
- Comes with docker
- Easy to deploy and manage
- ~20%/80%, 20% features 80% of use cases
- Runs anywhere Docker runs (built-in)
- Secure by default (Mutual TLS, encrypts control plane and db)
- Easier to troubleshoot

### Kubernetes
- The industry loves it
- Clouds will deploy/ manage Kubernetes for you
- Widest adoption and community
- Flexible: covers wides set of use cases

