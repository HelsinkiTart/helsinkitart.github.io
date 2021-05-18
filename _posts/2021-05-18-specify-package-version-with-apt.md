---
layout: post
title:  "Specifiy the package version with APT"
date:   2021-05-18 18:29:00 +0800
categories: ubuntu apt
---

Hello! First tech post, it's quick one...

I'm currently installing my Kubernetes learning envrinment using a couple of Ubuntu VMs.
My objective is to work to towards the certification using a given prodcut version.

Instead of installing the Kubernetes tool suite containing  _kubeadm_, _kubelet_ and _kubectl_ by doing:
```
apt-get install kubeadm kubelet kubectl
```

I specify the version of the package by executing the following command:
```
apt-get install kubeadm=1.20-00 ...
```
