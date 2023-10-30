# Day 02 - Why should I care?

Maybe you don't need to care about Cilium.

Seriously - there are a gazillion technologies out there and this might not be relevant to you. 

Maybe you're better off learning some AI stuff.

But if you happen to be involved in the world of:

- DevOps / Platform Engineering
- Networking
- Cloud like AWS, Azure or Google Cloud
- Kubernetes

Then it's very likely you're going to run into Cilium, if you haven't already.

## What should I know before I dedicate 100 Days of my life to this stuff?

Actually - let's break this down into 3 parts.

### What is the knowledge required to undertake the 100 Days of Cilium?

Pretty much all the hands-on you will be doing will be on Kubernetes clusters. There's just no way around it - you have to know *some* Kubernetes. 

I don't even expect you to run Kubernetes in production but I will expect you to have played with it - in home labs, on training courses, at work - but I won't put an artifical barrier (I started learning Cilium with a modest experience of Kubernetes and I did OK. I'm sure you will too). 

There are many courses that explain Kubernetes better than I ever could and my time is better spent on Cilium itself than around the underlying platform it's deployed on.

So I am expecting you to know about the following concepts:

- Containerised applications and the overall cloud native landscape
- General DevOps culture and practices knowledges
- Why Kubernetes?
- Kubernetes Architecture and Concepts, including Nodes, Pods, Services, Deployments
- Interacting with the Kubernetes API with `kubectl`
- Linux command line
- YAML
- Cloud Architecture concepts

You don't have to be a Linux wizard - I am certainly not - or be CKA certified - I am not either - but you won't enjoy this Cilium journey (for lack of a better word) if you've never touched Kubernetes.

And given that Cilium is a Cloud Networking Platform, well, you should know the basics of:

- TCP/IP Networking
- Firewalling and Networkg Security
- Load Balancing

Again - you don't have to be a networking or BGP expert (I will explain some of the basics where appropriate) but I will just have to assume a certain minimum level of knowledge.

### Who is this for?

Well, I wrote an entire blog post about it [here](https://isovalent.com/blog/post/cilium-learning-path/) so I won't repeat it all here... But if I had to recap quickly, Cilium is relevant for:

- Network Engineers, especially those that are now working on the cloud native space, with aspirations to do so.
- SecOps Engineers - Security professionals in the Cloud Native & DevOps space. 
- Platform Engineer / DevOps Engineer / SRE - anyone who may have to design, manage or operate Kubernetes clusters or Service Meshes.
- Cloud Architect / Cloud Engineer - anyone who might have to operate Kubernetes clusters managed by cloud providers (such as AWS EKS, AKS or GKE) where Cilium is deployed by default or frequently installed to replace or supplement the default CNI. This is also relevant for folks operating and running private clouds based on EKS-Anywhere (Cilium is the default CNI), Red Hat OpenShift, Tanzu, Rancher, etc...


### What will I learn ?

Well, you will learn what Cilium can do, how it works, its overall architecture and you will learn about many of the use cases it can help you with.
You will learn to install and configure Cilium. You will learn how to monitor it. 

You will learn how it works under the hood.

You will learn why some people start using it. 

You will learn where you get Cilium, even if you don't know it's there.

### How will I learn ?

You will learn by **reading**. There will be one guide such as this one for each day. I will add some links to docs, blog posts and other tutorials if you want to dive deeper.

You will learn by **doing**. There will be labs you can follow, either on your laptop or by going over to our labs over on [Isovalent.com](https://www.isovalent.com/labs).

You will learn by **watching**. I *intend* to record some videos for each day and I will also point you in the direction of videos already published on the respective Cilium and Isovalent YouTube channels.

