# 100DaysOfCilium
A repo where you can learn and try 100 different aspects and features of Cilium.

100 Days of Cilium will start in 2024, shortly after KubeCon Paris. Hope you join me in learning Cilium every day for 20 weeks (you get the weekends off).

## Purpose

This repo will help you learn 100 features and concepts of Cilium, the cloud networking platform. 

- Interested in becoming more proficient in Kubernetes networking?
- Are you Interested in Cilium but don't really know yet what it is about? 
- Already familiar with Cilium but looking at additional use cases ? 
- Think you're already a Cilium Jedi but want to test yourself?

If you've answered Yes to any of these questions, then this repo might be for you.

Vaguely inspired by Michael Cade's excellent [90 Days of DevOps](https://github.com/MichaelCade/90DaysOfDevOps) repo, this repo will provide a similar approach, albeit strictly focused on Cilium and related projects like Hubble.

Use this repo in addition to all the videos, labs and tutorials on the Isovalent [Resource Library](https://isovalent.com/resource-library/) and the official Cilium [documentation](https://docs.cilium.io/en/stable/) and you will become a Cilium pro in no time.

## Structure

Each feature or concept will be covered in a day or a series of days.

You don't have to strictly follow them in order, although the sequence of days was designed in a logical order.

Most guides will provide simple instructions to install and deploy Cilium to let you test on your own machine.

## Sources and references

This content will be for the vast majority new but where appropriate, I will re-use content I published elsewhere - tutorials, labs or blog posts I wrote on [Isovalent.com](https://isovalent.com). Of course, when I refer to sonebody else's content, I will attribute and give credit accordingly.


## Thanks

Thanks in advance to all the folks who help me understanding Cilium.

## Feedback, ideas and issues

- Please submit issues on this repo if you spot any mistakes.
- Feel free to submit Pull Requests if you would like to suggest your own fixes.
- If you have any suggestions for topics, please feel free to suggest them.

## Calendar

The calendar is, as of writing, a plan of the topics I might want to cover. Some of 

| Day | Topic |
| --- | --- |
| 1 | What is Cilium? |
| 2 | Why should I care? |
| 3 | Getting Started with the Star Wars demo |
| 4 | The role of Cilium in Kubernetes |
| 5 | Cilium Architecture |
| 6 | Cilium Agent |
| 7 | Cilium Operator |
| 8 | Cilium CLI |
| 9 | Installing Cilium |
| 10 | Cilium Node | 
| 11 | Cilium Endpoint |
| 12 | Cilium Identities |
| 13 | IP Address Management in Kubernetes |
| 14 | Cluster Scope IPAM |
| 15 | Kubernetes Host Scope IPAM |
| 16 | CRD-Backed IPAM |
| 17 | Multi-pool IPAM |
| 18 | Datapath Modes with Cilium |
| 19 | Tunnel Routing Mode |
| 20 | Native Routing Mode |
| 21 | Role of Network Policy in Kubernetes |
| 22 | Cilium Network Policy |
| 23 | Differences between Kubernetes Network Policies and Cilium Network Policies |
| 24 | L3 Network Policy |
| 25 | L4 Network Policy |
| 26 | L7 Network Policy |
| 27 | Network Policy Editor |
| 28 | Deny Policies |
| 29 | Host Firewall and Host Policies |
| 30 | Clusterwide Network Policies |
| 31 | Troubleshooting Network Policies |
| 32 | Monitoring Cilium with Prometheus and Grafana |
| 33 | What is eBPF? |
| 34 | What are some of the benefits offered by eBPF? |
| 35 | iptables & Kube-proxy |
| 36 | Kube-proxy replacement |
| 37 | Multi Cluster challenges |
| 38 | Cluster Mesh Architecture |
| 39 | Cluster Mesh installation and configuration |
| 40 | Service Affinity |
| 41 | What is Hubble? |
| 42 | Hubble Architecture |
| 43 | Hubble Relay |
| 44 | Hubble CLI |
| 45 | Hubble UI |
| 46 | Layer 7 Observability |
| 47 | What is Cilium Egress Gateway? |
| 48 | Egress Gateway Policy |
| 49 | External Workloads support |
| 50 | LB-IPAM |
| 51 | L2 Announcement |
| 52 | BGP in Kubernetes |
| 53 | Cilium BGP - Peering Policy |
| 54 | BGP Advanced Feature: Graceful Restart |
| 55 | BGP Advanced Feature: Custom Timers |
| 56 | BGP Advanced Feature: eBGP Multihop |
| 57 | BGP Advanced Feature: External Traffic Policy |
| 58 | Monitoring BGP on Cilium |
| 59 | What is a Service Mesh? |
| 60 | Which Service Mesh use cases can Cilium address? |
| 61 | What is Envoy? Which role does Envoy play in Cilium? |
| 62 | What is a sidecar? Why and how is Cilium removing the need for sidecars? |
| 63 | Envoy deployment models |
| 64 | What is Transparent Encryption? |
| 65 | Transparent Encryption with IPsec |
| 66 | Transparent Encryption with WireGuard |
| 67 | Mutual Authentication |
| 68 | Proxy Load Balancing for Kubernetes Services |
| 69 | What is Ingress in Kubernetes? |
| 70 | Cilium Ingress Controller |
| 71 | What is Gateway API in Kubernetes? |
| 72 | What are the differences between Ingress and Gateway API? |
| 73 | Migrating from Ingress to Gateway |
| 74 | Cilium Gateway API installation |
| 75 | Gateway API HTTP |
| 76 | Gateway API HTTPS Example and TLS Termination |
| 77 | Gateway API TLS Passthrough |
| 78 | Gateway API Traffic Splitting |
| 79 | Gateway API Header Request and Response Modifier |
| 80 | Gateway API Redirect |
| 81 | Gateway API Rewrite |
| 82 | Gateway API Mirror |
| 83 | Cross namespace routing |
| 84 | Cilium on GKE |
| 85 | Cilium on EKS |
| 86 | Cilium on EKS Anywhere |
| 87 | Cilium on AKS - BYOCNI |
| 88 | Cilium on AKS - Azure CNI Powered by Cilium |
| 89 | BBR |
| 90 | Bandwidth Manager |
| 91 | IPv6 on Kubernetes Cluster |
| 92 | Dual Stack Networking and Observability |
| 93 | BIG TCP with Cilium |
| 94 | Migrating to Cilium - Considerations |
| 95 | Seamless migration with CiliumNodeConfig |
| 96 | Contributing to Cilium |
| 97 | Suggesting changes to the Cilium Docs |
| 98 | Upgrading Cilium |
| 99 | Cilium Image Cosign |
| 100 | Cilium SBOM |

## What's after?

If 100 days aren't enough, you can continue your learning journey by exploring the following topics.

| Day | Topic |
| --- | --- |
| 101 | NAT46 |
| 102 | NAT64 |
| 103 | Cilium and Internal Traffic Policy |
| 104 | Masquerading |


