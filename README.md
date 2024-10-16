# Chris Samp's Public Github

This Github repo tracks public work as well as testing and experimental projects that are built out of interest, or trying certain concepts in publicly released employer software. These experiments may be to show a feature to a customer, but contain no customer or proprietary information. Much of the work I do is proprietary, or contains proprietary information, so cannot be shared publicly.

## Project Highlights

Pinned projects are what has been interesting to me lately.

## Kubernetes / Contour

A customer was having trouble allowing a trusted third party to access the kubeapi of a proxied kubernetes deployment. I built configuration to demonstrate how Contour could be used to terminate the trusted third party's TLS connection and re-encrypt/re-sign the request with internal certificates to deliver to kubeapi.
https://projectcontour.io/

## Cartographer / Supply Chain

Projects to create Cartographer configuration that allows interesting or novel workflows.
https://cartographer.sh/

## Java Spring

Many of the project use Spring because it is a tool I am familiar with, that has a lot of tooling to deploy to Cloud Foundry, Kubernetes and other targets.
https://spring.io/

## Cloud Foundry

Projects deploy various workloads to Cloud Foundry to test use cases. Typically the CF instance is Tanzu Application Service deployed on my ESXi Homelab, which is documented in a repository here.
https://www.cloudfoundry.org/
https://tanzu.vmware.com/content/blog/vmware-tanzu-application-service-6-0
https://docs.vmware.com/en/VMware-vSphere/index.html

## Tanzu Community Edition

Once upon a time in the ZIRP era, Tanzu was maintaining an open source Kubernetes distribution, with functional packages on top. While on loan to R&D for several weeks, I built the test suite for one of the modules in Go.
https://github.com/vmware-tanzu/community-edition/pull/3568/commits
https://github.com/vmware-tanzu/community-edition/tree/main/addons/packages/app-toolkit/0.1.0/test

## Microceph

Ceph is a cloud native blob storage platform. Microceph is a snap-based lightweight version that I deployed in my homelab to back the S3 protocol and act as blob storage for backups. I ran into some documentation gaps and corrected them for the project.
https://ceph.com/en/
https://github.com/canonical/microceph/
https://github.com/cgsamp/microceph/commit/18e403874d81db31fd63a69510e1e3d8e70b2f55

