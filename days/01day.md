# Day 01 - What is Cilium?

## Introduction

What is Cilium? Good question.

I tend to describe it broadly as a "cloud networking, security and observability platform".

Yeah, I know it doesn't exactly roll of the tongue. 

The thing is - Cilium can be many things.

Cilium is a Container Network Interface (CNI) plugin and what it is mostly known as.

Cilium is a firewall.

Cilium is a load-balancer.

Cilium is a proxy.

Cilium is (kinda) like a DHCP server.

Cilium is (kinda) like a VPN.

Cilium is a BGP-capable router.

Cilium is a NAT Gateway.

Cilium is a Service Mesh.

Cilium is a Service Controller.

Cilium is (kinda) like `tcpdump`.

That's why I end up calling it a "cloud networking, security and observability platform" - it can do *a lot of* things. 

And, most importantly, it can do a lot of things *well*. It is powered by a revolutionary Linux technology called eBPF. 

eBPF is what makes Cilium so fast - in feature velocity and in performance - but in many ways, it's slightly irrelevant. You can use and become a Cilium expert without having to learn anything about eBPF. But you might find it interesting and it explains how it came to be and how it performs so well, especially compared to some legacy technologies.

And knowing eBPF can be occasionnally handy when you need to troubleshoot Cilium. I will give it a lot of praise over the 100 Days of Cilium but it's not perfect. It can be a very complicated platform.

Hopefully, this series - and all the other content we are creating over on [Isovalent.com](https://www.isovalent.com) will reduce the barrier to adoption.


