---
title: Learn
description: An overview of the Kata Containers project

---

<p>Kata Containers are as light and fast as containers and integrate with the container management layers—including popular orchestration tools such as Docker and Kubernetes (k8s)—while also delivering the security advantages of VMs.</p>
<div class="columns">
  <div class="column"><a href="/collateral/kata-containers-1pager.pdf" class="button is-primary is-rounded">Project Overview</a>&nbsp;&nbsp;&nbsp;<a href="https://github.com/kata-containers/runtime/releases" class="button is-primary is-rounded">Latest Software Release</a><br/><br/>  
  </div>
</div>


<div class="columns">
  <div class="column">
   <image-modal imgurl="../images/katacontainers_architecture_diagram.jpg" />
  </div>
  
  <div class="column">
   <image-modal imgurl="../images/katacontainers_traditionalvskata_diagram.jpg" />
  </div>
</div>

<br>

## Kata Containers Project Update

<div class="video-wrapper">
  <iframe width="835 px" height="469.687 px" src="https://www.youtube.com/embed/pIODZrnqMDU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


## An Intro to Kata Containers

<div class="video-wrapper">
  <iframe width="835 px" height="469.687 px" src="https://www.youtube.com/embed/4gmLXyMeYWI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


## Demos

+ [Kata Containers configured in CRIO + K8s, utilizing both QEMU & Firecracker](https://asciinema.org/a/219790)

## Kata Containers in the News


+ [Kata Containers 1.5 release with support for Firecracker](https://aws.amazon.com/blogs/opensource/kata-containers-1-5-firecracker-support/) (AWS Open Source Blog | January 2019)
+ [Kata Containers one year anniversary](https://superuser.openstack.org/articles/kata-one-year-anniversary/) (Superuser | December 2018)
+ [Kata Containers support open container standards](https://superuser.openstack.org/articles/openstack-foundation-joins-open-container-initiative-kata/) (Superuser | March 2018)
+ [The Kata Containers project launches version 1.0 of its lightweight VMs for containers](https://techcrunch.com/2018/05/22/the-kata-containers-project-hits-1-0/) (TechCrunch | May 2018)
+ [Say hello to Kata Containers 1.0](https://superuser.openstack.org/articles/kata-containers-1-0/) (Superuser | May 2018)
+ [Why Kata Containers is good for the industry and customers](https://www.forbes.com/sites/janakirammsv/2017/12/11/why-kata-containers-is-good-for-the-industry-and-customers/#509177e7449e) (Forbes | December 2017)
+ [Kata Containers: secure, lightweight virtual machines for container environments](https://thenewstack.io/kata-containers-secure-lightweight-virtual-machines-container-environments/) (The New Stack | December 2017)

___

<h2 id="faq" class="h2_primary_dark"><a href="#faq" aria-hidden="true" class="header-anchor">#</a> FAQ</h2>


#### What's the advantage of Kata Containers?
Kata Containers perform like containers, but provide the workload isolation and security advantages of VMs. It combines the benefits of containers and VMs.


#### Who uses Kata Containers?
Kata Containers is still in its formational stages, but the technical basis for the project--Clear Containers and runV--are used globally at enterprise scale by organizations like JD.com, China's largest ecommerce company (by revenue).


#### Will this require a rebuild of my Docker containers? Does it work with Kubernetes?
Kata Containers is OCI (Open Container Initiative) compliant, the same standard shared by Docker containers as well as the container runtime interface (CRI) for Kubernetes.


#### What's the operating system? Do I get to pick that?
Kata Containers supports Linux (host and guest) for now. On the host side, we have installation instructions for several popular distributions. We also have out-of-the-box support for Clear Linux, Fedora, and CentOS 7 rootfs images through the OSBuilder which can also be used to roll your own guest images.


#### What's the license for Kata Containers?
Kata Containers is open source and licensed under the Apache 2.0 license, which means it is free to use, free to distribute, and does not require modifications to be contributed back to the project. Read more about Apache 2.0.


#### Where is the code?
You can find the code at [github.com/kata-containers](https://github.com/kata-containers). You won't see much yet, as Clean Containers and runV cores are currently merging the code bases, but you can expect Kata Containers code to be ready around the end of Q2 2018. You can find links to the original repositories from Intel and Hyper.sh on the [katacontainers.io](https://katacontainers.io) homepage.


#### Can I contribute to it?
Yes! Kata Containers is open source, which means it relies on contributors like you! After the initial code base merger, all areas of Kata Containers will be open for contribution. Between now and the merger completion, you can contribute:
+ Unit tests for agent, shim and proxy
+ PR reviews for agent and shim
+ OSbuilder support for more distros
+ gRPC input (Do we cover it all?)
+ Features Requests: Open issues and PRs for any feature that you’d like to see in Kata Containers!



#### How is Kata Containers governed?
Kata Containers is driven by an Architecture Committee. The Architecture Committee, whose members are elected by contributors, oversees architectural decisions, including standardization, and resolves technical disagreements between project maintainers. Kata Containers is managed by the OpenStack Foundation, which provides event organization, code of conduct management, and other administrative support.


#### Are there Kata meetups?
We don't have any scheduled yet, but you can expect to see some on the calendar soon! Want to organize a Kata Containers Meetup? Email info at katacontainers.io to get involved.


#### Is this an OpenStack project?
Kata Containers is managed by the OpenStack Foundation, but is not a part of the OpenStack cloud infrastructure project. From a technical perspective, Kata Containers can be run on OpenStack, but can also be run on other cloud solutions like Azure and Google Cloud Platform. The OpenStack Foundation brings its 8 years of open source project and community management to this new project to provide community support, technical structure, and event management.
