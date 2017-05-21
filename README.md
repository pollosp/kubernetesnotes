# Kubernetes notes and refereces
## Resources

### Flavour
* [Rancheros](http://rancher.com/kubernetes/)
* [Tectonic](https://coreos.com/tectonic/)
* [Heptio](https://www.heptio.com/)
* [Kops](https://github.com/kubernetes/kops)
* [Track](https://github.com/kz8s/tack)
* [Kubernetes the hardway](https://github.com/kelseyhightower/kubernetes-the-hard-way)
* [Deis](https://deis.com/)
* [OpenShift v3](https://bloHg.openshift.com/openshift-v3-platform-combines-docker-kubernetes-atomic-and-more/) 
* [Openshift options](https://www.quora.com/What-is-the-difference-between-OpenShift-Origin-Online-and-Enterprise)

### Basics
* [Key Concepts of Kubernetes](http://blog.arungupta.me/key-concepts-kubernetes/)
* [Kubernetes under the Hood](https://github.com/kubernetes/community/blob/master/contributors/design-proposals/aws_under_the_hood.md)
* [State and Storage](https://blog.openshift.com/kubernetes-state-storage/#.WSAsjYC7GYM.twitter)
* [The Three Pillars of Kubernetes Container Orchestration](https://medium.com/@Rancher_Labs/the-three-pillars-of-kubernetes-container-orchestration-247f42115a4a)

### Test environments
* [Minikube](https://github.com/kubernetes/minikube)
* [Minishift](https://github.com/minishift/minishift)
* [Scaling developer environments with kubernetes](https://blog.branch.io/beta-architecture-scaling-developer-environments-with-kubernetes/)

### Monitoring
* [Prometheus operator](https://coreos.com/blog/the-prometheus-operator.html)
* [Monitoring with Prometheus](https://coreos.com/blog/monitoring-kubernetes-with-prometheus.html)
* [Heapster](https://github.com/kubernetes/heapster)
* [Monitoring with Heapster](https://deis.com/blog/2016/monitoring-kubernetes-with-heapster/)
* [Sysdig](https://sysdig.com/blog/monitoring-kubernetes-with-sysdig-cloud/)
* [Honeycombio](https://github.com/honeycombio/honeycomb-kubernetes-agent)
* [Rethinking monitoring for containers](https://thenewstack.io/monitoring-reset-containers/)

### H.A
* [Federation](https://www.youtube.com/watch?v=pq9lbkmxpS8&t=37s)
* [Kops pushing updates without reboot](https://github.com/kubernetes/kops/blob/master/docs/work_in_progress/pushing_updates_without_rebooting.md)
* [Kops federation](https://github.com/kubernetes/kops/blob/master/docs/high_availability.md)
* [Experimenting with cross cloud kubernetes](https://medium.com/@samnco/experimenting-with-cross-cloud-kubernetes-cluster-federation-dfa99f913d54#.78sux79h8)
* [Federated ingress](https://kubernetes.io/docs/tasks/administer-federation/ingress/)
* [Self-hosted, Scale, and Federation with Kubernetes v1.4 and Beyond](https://www.youtube.com/watch?v=3G8uWxVDQcE)
* [Kubernetes Replication Controller, Replica Set and Deployments: Understanding replication options](https://www.mirantis.com/blog/kubernetes-replication-controller-replica-set-and-deployments-understanding-replication-options/)
* [Kubernetes cluster federation tutorial](https://github.com/kelseyhightower/kubernetes-cluster-federation)

### Stateful apps
* [Run and Scale Stateful Applications Easily in Kubernetes](http://blog.kubernetes.io/2016/12/statefulset-run-scale-stateful-applications-in-kubernetes.html)
* [https://opensource.com/article/17/2/stateful-applications](http://blog.kubernetes.io/2017/02/postgresql-clusters-kubernetes-statefulsets.html)
* [http://blog.kubernetes.io/2017/02/postgresql-clusters-kubernetes-statefulsets.html](https://opensource.com/article/17/2/stateful-applications)

### Networking
* [Flannel](https://github.com/coreos/flannel)
* [Calico](https://www.projectcalico.org/calico-networking-for-kubernetes/)
* [Aporeto Trireme](https://www.aporeto.com/trireme-architecture/ )
* [Wave](https://www.weave.works/) 
* [Wave @ Fosdem](https://youtu.be/bO3gQL9JgRE)
* [Tigera](https://www.sdxcentral.com/articles/news/calico-flannel-tigera-new-container-networking-startup/2016/05/)
* [Canal](https://github.com/projectcalico/canal)

### Ingress (Load Balancer L7)
* [Ingress basics](https://youtu.be/Syw2PzRudIM)
* [Traefik](https://github.com/containous/traefik)
* [Fabio](https://github.com/eBay/fabio)
* [Traefik example](https://youtu.be/19_SdVU4cdc)

### Microservice routing
* [Linkerd](https://linkerd.io/)
* [Monzo](https://speakerdeck.com/olix0r/when-failure-is-not-an-option-processing-real-money-at-monzo-with-kubernetes-and-linkerd)

### Secret Management
* [Example 1](https://m.youtube.com/watch?v=N41ZwsORs_g)
* [Example 2](https://m.youtube.com/watch?v=N41ZwsORs_g)
* [Hashicorp Vault example 1](https://www.youtube.com/watch?v=kb7DU-Qwtrc)

### CI/CD
* [Helm](https://github.com/kubernetes/helm/blob/master/README.md  )  
* [Bulding Helm charts](https://github.com/kubernetes/helm/blob/master/docs/charts.md)
* [CI/CD with Kubernetes and Helm](https://m.youtube.com/watch?v=jEF8S-966sY)
* [Delivering Kubernetes native applications](https://youtu.be/zBc1goRfk3k)
* [Cloud Pipeline with Aritfactory](https://m.youtube.com/watch?v=o7NeTV7uUuA)
* [Cloud Pipeline with Aritfactory 2](https://m.youtube.com/watch?v=rVoR6PIimiI)
* [Wercker](http://www.wercker.com/)
* [Wercker example](https://youtu.be/PXLL3e7iW40)
* [Wercker deploy example](https://coreos.com/blog/building-minimal-containers-with-quay-kubernetes-wercker.html)
* [CI/CD with Helm and Wercker](https://m.youtube.com/watch?v=kmH5DWtdGf4)
* [Simple pipeline with Jenkins](https://youtu.be/NVoln4HdZOY)

### Security
* [Clair](https://github.com/coreos/clair/blob/master/README.md)
* [Conjur](https://www.conjur.com/product)
* [Conjur Examples](https://m.youtube.com/watch?v=8Pw1R7T_ibE) 
* [Hashicorp Vault talk](https://www.youtube.com/watch?v=skENC9aXgco)
* [Dagda](https://github.com/eliasgranderubio/dagda)
* [Understanding Kubernetes Authentication and Authorization
](http://cloudgeekz.com/1045/kubernetes-authentication-and-authorization.html)
* [Kube2IAM](https://github.com/jtblin/kube2iam)


### Bulding Docker images
* [Bulding images in GKE](https://cloudplatform.googleblog.com/2017/03/Google-Cloud-Container-Builder-a-fast-and-flexible-way-to-package-your-software.html?m=1)
* [Docker base image](https://docs.docker.com/engine/userguide/eng-image/baseimages/)
* [How to docker images](http://www.projectatomic.io/docs/docker-building-images/)
* [Packer,docker,kubernetes](https://cloud.google.com/solutions/automated-build-images-with-jenkins-kubernetes) 
* [Packer example](https://github.com/tcnksm-sample/packer-docker/blob/master/machine_chef.json)
* [Buildig docker images with Buddy](https://buddy.works/blog/introducing-build-docker-image)

### Container patterns
* [Container patterns Hot 16](https://www.usenix.org/system/files/conference/hotcloud16/hotcloud16_burns.pdf)
 
### Troubleshooting
* [Fosdem 17](https://fosdem.org/2017/schedule/event/troubleshootkube/)
* [Application troubleshooting](https://kubernetes.io/docs/user-guide/application-troubleshooting/)
* [Service Troubleshooting](https://kubernetes.io/docs/user-guide/debugging-services/)

### Talks
* [AWS introduction to container management](https://m.youtube.com/watch?v=nkguMBVsRbE)
* [Hightower Hashiconf 2016](https://m.youtube.com/watch?v=Nosa5-xcATw)
* [Hightower PuppetConf 2016](https://m.youtube.com/watch?v=HlAXp0-M6SY) 
* [Kubernetes Best Paractices Google I/O 2016](https://m.youtube.com/watch?v=21hXNReWsUU) 
* [Kubernetes for Childerns](https://m.youtube.com/watch?v=4ht22ReBjno)
* [Kubernetes getting started](https://m.youtube.com/watch?v=_vHTaIJm9uY)
* [Kubernetes in 15 minutes](https://m.youtube.com/watch?v=o85VR90RGNQ)
* [Container management and deployment: from development to production (Google Cloud Next '17)](https://youtu.be/XL9CQobFB8I)

### Courses
* [Udacity - Scalable Microservices with Kubernetes (Beginner)](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615)

### Experiences
* [One year with kubernetes 1](https://www.google.es/amp/s/techbeacon.com/one-year-using-kubernetes-production-lessons-learned%3Famp)
* [One year with kubernetes 2](https://acotten.com/post/1year-kubernetes)
* [One year with Kubernetes 3](http://events.linuxfoundation.org/sites/events/files/slides/LinuxCon%2BContainerCon-%20%20One%20year%20of%20Deploying%20Applications%20with%20Docker,%20CoreOS,%20Kubernetes%20and%20Co.pdf)
* [Lessons learned from three container-management systems over a decade](http://queue.acm.org/detail.cfm?id=2898444)
* [Three lessons from running Kubernetes in production](http://labs.unacast.com/2016/01/27/three-lessons-from-running-k8s-in-production/)
* [10 Most common reasons kubernetes deployments fail part 1](https://www.google.es/amp/s/kukulinski.com/10-most-common-reasons-kubernetes-deployments-fail-part-1/amp/)
* [Containers in production](http://unethicalblogger.com/2017/03/14/on-containers-in-production.html)