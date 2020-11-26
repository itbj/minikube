# 20201127T0330 Installed on a VM, ubuntu 19.10 ,virtualbox 6.0. 👍 minikube Running successfully！  
$ minikube start  
😄  minikube v1.15.1 on Ubuntu 19.10  
✨  Using the virtualbox driver based on existing profile  
👍  Starting control plane node minikube in cluster minikube  
🔥  Creating virtualbox VM (CPUs=2, Memory=2200MB, Disk=20000MB) ...  
^[$❗  This VM is having trouble accessing https://k8s.gcr.io  
💡  To pull new external images, you may need to configure a proxy: https://minikube.sigs.k8s.io/docs/reference/networking/proxy/    
🐳  Preparing Kubernetes v1.19.4 on Docker 19.03.13 ...  
🔎  Verifying Kubernetes components...  
🌟  Enabled addons: storage-provisioner, default-storageclass  
💡  kubectl not found. If you need it, try: 'minikube kubectl -- get pods -A'  
🏄  Done! kubectl is now configured to use "minikube" cluster and "default" namespace by default

# minikube

[![Actions Status](https://github.com/kubernetes/minikube/workflows/Master/badge.svg)](https://github.com/kubernetes/minikube/actions)
[![GoReport Widget]][GoReport Status]
[![Github All Releases](https://img.shields.io/github/downloads/kubernetes/minikube/total.svg)](https://github.com/kubernetes/minikube/releases/latest)
[![Latest Release](https://img.shields.io/github/v/release/kubernetes/minikube?include_prereleases)](https://github.com/kubernetes/minikube/releases/latest)
 

[GoReport Status]: https://goreportcard.com/report/github.com/kubernetes/minikube
[GoReport Widget]: https://goreportcard.com/badge/github.com/kubernetes/minikube

<img src="https://github.com/kubernetes/minikube/raw/master/images/logo/logo.png" width="100" alt="minikube logo">

minikube implements a local Kubernetes cluster on macOS, Linux, and Windows. minikube's [primary goals](https://minikube.sigs.k8s.io/docs/concepts/principles/) are to be the best tool for local Kubernetes application development and to support all Kubernetes features that fit. 

<img src="https://raw.githubusercontent.com/kubernetes/minikube/master/site/static/images/screenshot.png" width="575" height="322" alt="screenshot">

## Features

minikube runs the latest stable release of Kubernetes, with support for standard Kubernetes features like:

* [LoadBalancer](https://minikube.sigs.k8s.io/docs/handbook/accessing/#loadbalancer-access) - using `minikube tunnel`
* Multi-cluster - using `minikube start -p <name>`
* NodePorts - using `minikube service`
* [Persistent Volumes](https://minikube.sigs.k8s.io/docs/handbook/persistent_volumes/)
* [Ingress](https://kubernetes.io/docs/tasks/access-application-cluster/ingress-minikube/)
* [Dashboard](https://minikube.sigs.k8s.io/docs/handbook/dashboard/) - `minikube dashboard`
* [Container runtimes](https://minikube.sigs.k8s.io/docs/handbook/config/#runtime-configuration) - `start --container-runtime`
* [Configure apiserver and kubelet options](https://minikube.sigs.k8s.io/docs/handbook/config/#modifying-kubernetes-defaults) via command-line flags

As well as developer-friendly features:

* [Addons](https://minikube.sigs.k8s.io/docs/handbook/deploying/#addons) - a marketplace for developers to share configurations for running services on minikube
* [NVIDIA GPU support](https://minikube.sigs.k8s.io/docs/tutorials/nvidia_gpu/) - for machine learning
* [Filesystem mounts](https://minikube.sigs.k8s.io/docs/handbook/mount/)

**For more information, see the official [minikube website](https://minikube.sigs.k8s.io)**

## Installation

See the [Getting Started Guide](https://minikube.sigs.k8s.io/docs/start/)

:mega: **Please fill out our [fast 5-question survey](https://forms.gle/Gg3hG5ZySw8c1C24A)** so that we can learn how & why you use minikube, and what improvements we should make. Thank you! :dancers:

## Documentation

See https://minikube.sigs.k8s.io/docs/

## More Examples

See minikube in action [here](https://minikube.sigs.k8s.io/docs/handbook/controls/)

## Community

minikube is a Kubernetes [#sig-cluster-lifecycle](https://github.com/kubernetes/community/tree/master/sig-cluster-lifecycle)  project.

* [**#minikube on Kubernetes Slack**](https://kubernetes.slack.com) - Live chat with minikube developers!
* [minikube-users mailing list](https://groups.google.com/forum/#!forum/minikube-users)
* [minikube-dev mailing list](https://groups.google.com/forum/#!forum/minikube-dev)

* [Contributing](https://minikube.sigs.k8s.io/docs/contrib/)
* [Development Roadmap](https://minikube.sigs.k8s.io/docs/contrib/roadmap/)

Join our meetings:
* [Bi-weekly office hours, Mondays @ 11am PST](https://tinyurl.com/minikube-oh)
* [Triage Party](https://minikube.sigs.k8s.io/docs/contrib/triage/)
