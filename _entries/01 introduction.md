---
sectionid: intro
sectionclass: h1
title: Red Hat OpenShift Workshop
type: nocount
is-parent: yes
---

[Red Hat OpenShift](https://www.redhat.com/en/technologies/cloud-computing/openshift) is the industry's leading hybrid cloud application platform powered by Kubernetes. OpenShift delivers a consistent experience across public cloud, on-premise, hybrid cloud, or edge architecture. In this lab, you'll go through a set of tasks that will help you understand some of the concepts of deploying and securing container based applications on top of Red Hat OpenShift.

You can use this guide as an OpenShift tutorial and as study material to help you get started to learn OpenShift.

Some of the things you’ll be going through:

- Creating a [project](https://docs.openshift.com/container-platform/latest/applications/projects/working-with-projects.html) on the Red Hat OpenShift Web Console
- Deploying a MongoDB container that uses cloud storage for [persistence](https://docs.openshift.com/container-platform/latest/storage/understanding-persistent-storage.html)
- Restoring data into the MongoDB container by [executing commands](https://docs.openshift.com/container-platform/latest/nodes/containers/nodes-containers-remote-commands.html) on the Pod
- Deploying a Node JS API and frontend app from Git Hub using [Source-To-Image (S2I)](https://docs.openshift.com/container-platform/latest/openshift_images/create-images.html)
- Exposing the web application frontend using [Routes](https://docs.openshift.com/container-platform/latest/networking/routes/route-configuration.html)
- Creating a [network policy](https://docs.openshift.com/container-platform/4.13/networking/network_policy/about-network-policy.html) to control communication between the different tiers in the application

You'll be doing the majority of the labs using the OpenShift CLI, but you can also accomplish them using the Red Hat OpenShift web console.
