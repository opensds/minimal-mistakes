---
title: OpenSDS Installer - Salt
author: Noel McLoughlin
header:
  image: /assets/images/osds2.png
categories:
  - Enhancement
tags:
  - bali
---

The OpenSDS Bali installer tool is a group of projects designed to simplify
cluster deployment and configuration. In the recent Bali release, we officially
support both "Ansible" and "Helm" for deployment management of OpenSDS cluster.

Today Salt has been added as an experimental alternative installer. In the OpenSDS community we belive a diversity of deployment methods improves the mindshare and promotes the further adoption of OpenSDS by our members and users.

A massive thank you to the OpenSDS community for their support.

### OpenSDS Salt Installer

The "opensds-installer/salt" has the following functionality:

* Lightweight implementation in OpenSDS project. Simple INSTALL procedure.
* Transparent yaml modelling for data-driven orchestration.
* A single configuration file for site and release customizations.
* Support for Ubuntu and CentOS (extensible).
* Upstream [OpenSDS formula](https://github.com/saltstack-formulas/opensds-formula) repository.

### Further details

The opensds-installer consists of projects to simplify cluster deployment.

[OpenSDS Installer](https://github.com/opensds/opensds-installer/releases/tag/v0.4.0)

Salt, available under the Apache 2.0 license, is described as "Software to automate the management and configuration of any infrastructure or application at scale".  Three developer communities drive the salt ecosystem:

[Salt](https://github.com/saltstack/salt) community.

[saltstack formulas](https://github.com/saltstack-formulas) community.

[salt formulas](https://github.com/salt-formulas) community.
