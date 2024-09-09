---
layout: project
type: project
image: img/azureansible/icon.png
title: "Azure Ansible Collection"
date: 2022
published: true
labels:
  - Ansible
  - Azure
  - OpenSource
  - GitHub
summary: "Ansible collection to manage azure resources."
---

<img class="img-fluid" src="../img/azureansible/icon.png">

I contributed to the open-source "Azure Ansible Collection" project on GitHub, where I added missing objects and elements to the configuration of Azure's Application Gateway service. 

Here's a list of the modifications I made:
* add waf configuration settings
* add trusted root certificates
* add enable http 2 parameter
* add autoscale configuration
* add draining options

I also updated the integration tests and documentation to reflect the changes I made in the configuration of Azure's Application Gateway service.

Source: <a href="https://github.com/ansible-collections/azure/pull/990"><i class="large github icon "></i>Pull Request</a>

