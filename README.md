# k8s-is-not-a-paas

[![License: CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-sa/4.0/)

Diagram aiming to explain the differences in functionality between:

* IaaS
* Cloud Foundry deployed with BOSH
* Kubernetes
* Kubernetes-as-a-Service
* Cloud Foundry deployed on Kubernetes

![Comparison of IaaS, PaaS and KaaS](/iaas-kubes-paas.svg?raw=true)

## Intention

The diagram aims to illustrate the difference in functionality between PaaSes like Cloud Foundry, and 'raw' Kubernetes. We have encountered many folks asking "should I use Cloud Foundry or Kubernetes", not realising that they are very different things.

The diagram does _not_ indicate that the functionality 'missing' from Kubernetes cannot be added, rather that these don't come preconfigured 'out of the box'. You will need to configure in-built primitives (e.g. RBAC), choose plugins (e.g. CNI), choose extensions (e.g. cluster DNS, ingresses, log aggregation), configure all of those, keep them all patched, and also test that new versions work nicely together.

## Usage Terms

Please feel free to use and remix. Please attribute and do not place more restrictive licenses on adaptations.

This diagram is licensed with Creative Commons By-ShareAlike International 4.0.

_The diagram was exported from Google Slides, so apologies for the awful SVG markup._
