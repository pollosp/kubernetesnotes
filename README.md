# Kubernetes notes and refereces
## Resources

### Flavour
* [Rancheros](http://rancher.com/kubernetes/)
* [Tectonic](https://coreos.com/tectonic/)
* [Heptio](http://docs.heptio.com/content/tutorials/aws-cloudformation-k8s.html)
* [Kops](https://github.com/kubernetes/kops)
* [Track](https://github.com/kz8s/tack)
* [Kubernetes the hardway](https://github.com/kelseyhightower/kubernetes-the-hard-way)
* [Deis](https://deis.com/)
* [OpenShift v3](https://bloHg.openshift.com/openshift-v3-platform-combines-docker-kubernetes-atomic-and-more/)
* [Openshift options](https://www.quora.com/What-is-the-difference-between-OpenShift-Origin-Online-and-Enterprise)
* [Kublr](http://kublr.com/)
* [Kubo](https://pivotal.io/partners/kubo)
* [Kubicorn](https://github.com/kris-nova/kubicorn)
* [k8s-snowflake](https://github.com/jessfraz/k8s-snowflake)

### Basics
* [Key Concepts of Kubernetes](http://blog.arungupta.me/key-concepts-kubernetes/)
* [Kubernetes under the Hood](https://github.com/kubernetes/community/blob/master/contributors/design-proposals/aws_under_the_hood.md)
* [State and Storage](https://blog.openshift.com/kubernetes-state-storage/#.WSAsjYC7GYM.twitter)
* [The Three Pillars of Kubernetes Container Orchestration](https://medium.com/@Rancher_Labs/the-three-pillars-of-kubernetes-container-orchestration-247f42115a4a)
* [Comparison of container schedulers](https://medium.com/@ArmandGrillet/comparison-of-container-schedulers-c427f4f7421)
* [Kubernetes 1.6 new features](https://www.brighttalk.com/webcast/14601/262767)
* [Best practices with kubernetes](https://github.com/arschles/kube-best-practices)
* [What happend when k8s ... ](https://github.com/jamiehannaford/what-happens-when-k8s)

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
* [Federation with StackpointCluoud](https://blog.stackpoint.io/simplifying-kubernetes-federation-building-the-enterprise-infrastructure-highway-4e333a75bb24)

### Stateful apps
* [Run and Scale Stateful Applications Easily in Kubernetes](http://blog.kubernetes.io/2016/12/statefulset-run-scale-stateful-applications-in-kubernetes.html)
* [https://opensource.com/article/17/2/stateful-applications](http://blog.kubernetes.io/2017/02/postgresql-clusters-kubernetes-statefulsets.html)
* [http://blog.kubernetes.io/2017/02/postgresql-clusters-kubernetes-statefulsets.html](https://opensource.com/article/17/2/stateful-applications)
* [Ruby migrations](http://blog.bigbinary.com/2017/06/16/managing-rails-tasks-such-as-db-migrate-and-db-seed-on-kuberenetes-while-performing-rolling-deployments.html)

### Networking
* [Flannel](https://github.com/coreos/flannel)
* [Calico](https://www.projectcalico.org/calico-networking-for-kubernetes/)
* [Aporeto Trireme](https://www.aporeto.com/trireme-architecture/ )
* [Wave](https://www.weave.works/)
* [Wave @ Fosdem](https://youtu.be/bO3gQL9JgRE)
* [Tigera](https://www.sdxcentral.com/articles/news/calico-flannel-tigera-new-container-networking-startup/2016/05/)
* [Canal](https://github.com/projectcalico/canal)
* [Network policies](https://github.com/ahmetb/kubernetes-network-policy-recipes)
* [Amazon VPC CNI](https://github.com/aws/amazon-vpc-cni-k8s)
* [NodePort vs LoadBalancer vs Ingress](https://medium.com/google-cloud/kubernetes-nodeport-vs-loadbalancer-vs-ingress-when-should-i-use-what-922f010849e0)
* [Container networking](https://github.com/mhausenblas/cn-ref)

### Ingress (Load Balancer)
* [Ingress basics](https://youtu.be/Syw2PzRudIM)
* [Traefik](https://github.com/containous/traefik)
* [Fabio](https://github.com/eBay/fabio)
* [Traefik example](https://youtu.be/19_SdVU4cdc)
* [Lets encrypt](https://medium.com/google-cloud/from-zero-to-hero-run-parse-server-on-google-cloud-platform-part-3-automatically-obtain-lets-d7db8994000a)
* [Envoy](https://www.envoyproxy.io/)
* [Heptio Contour](https://github.com/heptio/contour)

### Microservice routing
* [Linkerd](https://linkerd.io/)
* [Monzo](https://speakerdeck.com/olix0r/when-failure-is-not-an-option-processing-real-money-at-monzo-with-kubernetes-and-linkerd)
* [Istio](https://istio.io/)

### Secret Management
* [Example 1](https://m.youtube.com/watch?v=N41ZwsORs_g)
* [Example 2](https://m.youtube.com/watch?v=N41ZwsORs_g)
* [Hashicorp Vault example 1](https://www.youtube.com/watch?v=kb7DU-Qwtrc)
* [Pods, Tokens, and a Little Glue: Integrating Kubernetes and Vault in Elastic Infrastructure](https://www.elastic.co/blog/kubernetes-vault-integration-devops-team)
* [Bitami sealed secrets](https://github.com/bitnami/sealed-secrets)

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
* [Argo](https://github.com/argoproj/arg)
* [Jenkins X](https://jenkins.io/blog/2018/03/19/introducing-jenkins-x/index.html)

### Security
* [Clair](https://github.com/coreos/clair/blob/master/README.md)
* [Conjur](https://www.conjur.com/product)
* [Conjur Examples](https://m.youtube.com/watch?v=8Pw1R7T_ibE)
* [Hashicorp Vault talk](https://www.youtube.com/watch?v=skENC9aXgco)
* [Dagda](https://github.com/eliasgranderubio/dagda)
* [Understanding Kubernetes Authentication and Authorization
](http://cloudgeekz.com/1045/kubernetes-authentication-and-authorization.html)
* [Kube2IAM](https://github.com/jtblin/kube2iam)
* [Heptio authenticator (IAM)](https://github.com/heptio/authenticator)
* [RBAC best practices](http://docs.heptio.com/content/tutorials/rbac.html)
* [Building Container Images Securely on Kubernetes](https://blog.jessfraz.com/post/building-container-images-securely-on-kubernetes/)
* [kubernetes security best practices](https://github.com/freach/kubernetes-security-best-practice)


### Bulding Docker images
* [Bulding images in GKE](https://cloudplatform.googleblog.com/2017/03/Google-Cloud-Container-Builder-a-fast-and-flexible-way-to-package-your-software.html?m=1)
* [Docker base image](https://docs.docker.com/engine/userguide/eng-image/baseimages/)
* [How to docker images](http://www.projectatomic.io/docs/docker-building-images/)
* [Packer,docker,kubernetes](https://cloud.google.com/solutions/automated-build-images-with-jenkins-kubernetes)
* [Packer example](https://github.com/tcnksm-sample/packer-docker/blob/master/machine_chef.json)
* [Building docker images with Buddy](https://buddy.works/blog/introducing-build-docker-image)

### Container patterns
* [Container patterns Hot 16](https://www.usenix.org/system/files/conference/hotcloud16/hotcloud16_burns.pdf)

### Troubleshooting
* [Fosdem 17](https://fosdem.org/2017/schedule/event/troubleshootkube/)
* [Application troubleshooting](https://kubernetes.io/docs/user-guide/application-troubleshooting/)
* [Service Troubleshooting](https://kubernetes.io/docs/user-guide/debugging-services/)

### External DNS
* [CloudFlare](https://github.com/kubernetes-incubator/external-dns/pull/140)

### CRD
* [Kubernetes deep dive code generation customresources](https://blog.openshift.com/kubernetes-deep-dive-code-generation-customresources/)
* [CRD RDS example](https://github.com/MYOB-Technology/ops-kube-db-operator?files=1)
* [Heptio controller example](https://github.com/jbeda/tgik-controller)

### Scheduling
* [Advanced Scheduling in Kubernetes](http://blog.kubernetes.io/2017/03/advanced-scheduling-in-kubernetes.html)
* [Kubernetes: Advanced Scheduling Controls](https://www.youtube.com/watch?v=qewfWj_zOgI)
* [Tolerations and taints](https://docs.openshift.com/container-platform/3.6/admin_guide/scheduling/taints_tolerations.html)
* [Kubernetes Engine Priority and Preemption](https://cloudplatform.googleblog.com/2018/02/get-the-most-out-of-Google-Kubernetes-Engine-with-Priority-and-Preemption.html)
* [Preemption and Priority](https://kubernetes.io/docs/concepts/configuration/pod-priority-preemption/)

### Videos
* [AWS introduction to container management](https://m.youtube.com/watch?v=nkguMBVsRbE)
* [Hightower Hashiconf 2016](https://m.youtube.com/watch?v=Nosa5-xcATw)
* [Hightower PuppetConf 2016](https://m.youtube.com/watch?v=HlAXp0-M6SY)
* [Kubernetes Best Paractices Google I/O 2016](https://m.youtube.com/watch?v=21hXNReWsUU)
* [Kubernetes for Childerns](https://m.youtube.com/watch?v=4ht22ReBjno)
* [Kubernetes getting started](https://m.youtube.com/watch?v=_vHTaIJm9uY)
* [Kubernetes in 15 minutes](https://m.youtube.com/watch?v=o85VR90RGNQ)
* [Container management and deployment: from development to production (Google Cloud Next '17)](https://youtu.be/XL9CQobFB8I)
* [Heptio youtube channel](https://www.youtube.com/channel/UCjQU5ZI2mHswy7OOsii_URg)

### Addons/Tools
* [Ksonnet](http://ksonnet.heptio.com/)
* [Draft](https://github.com/Azure/draft)
* [Metaparticle](https://metaparticle.io/)
* [Sonobuoy](https://github.com/heptio/sonobuoy)
* [ARK](https://github.com/heptio/ark)
* [Brigade](https://github.com/Azure/brigade)
* [Skaffold](https://t.co/4YC4O8Z6ky)
* [kubectx](https://github.com/ahmetb/kubectx)
* [kube-ps1](https://github.com/jonmosco/kube-ps1)
* [Draft vs Gitkube vs Helm vs Ksonnet vs Metaparticle vs Skaffold](https://blog.hasura.io/draft-vs-gitkube-vs-helm-vs-ksonnet-vs-metaparticle-vs-skaffold-f5aa9561f948)

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
* [Operating Kubernetes @ stripe](https://stripe.com/blog/operating-kubernetes)
* [Make Kubernetes Production Ready](https://youtu.be/tbD6Rcm2sI8)
* [Scaling up with Google Kubernetes Engine: our experience after 6 months in production](https://medium.com/streamroot-developers-blog/scaling-up-with-google-kubernetes-engine-our-experience-after-6-months-in-production-ec9e21cd5fce)
