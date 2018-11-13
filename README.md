# kubecon2018-CHINA 
## 11.13 Lightning talk
**Take the Wheel, Don’t Reinvent It! - Deploying Apps With Helm in 5 Minutes - Christopher Hanson, RX-M Enterprises, LL**
So you’ve deployed Kubernetes, now what? Time to deploy your applications! First things first, describe a Deployment to control your Pods--it is probably going to need a Secret or two and maybe a ConfigMap too! Now specify a Service to give it a VIP and introduce an Ingress to expose it! Saving some data? Propose a PVC! What about adding a Service Account or CRB? Lost in alliterations and acronyms? Helm is here to help!

This lighthearted session introduces Helm in an approachable way: revealing its architecture and nomenclature; introducing Charts, Chart components, and the official Charts repository for curated apps; as well as explaining Releases and Release upgrades. Information will be presented in a platform agnostic way to show attendees how to read, customize, and deploy an existing Chart to fit their needs, whether in the cloud, on a given platform or in their own datacenter.
click here for slide [Helm_ckhanson_KubeConChina](https://drive.google.com/open?id=1vW_26CIUKYGc4VZNLL5xPoOQTtedo8Pm)

**From Enterprise Image Registry to Chart Repository - Tan Jiang, VMware**
HARBOR: as the Kubernetes Registry.  
In the On-Prem enterprise environment, we've been packaging content into docker images and hosting them using docker registry for some time, now helm chart has become the choice of application package format on Kubernetes, it's time to explore what's the proper way to host Helm Charts.

Based on our experience extending a private docker image registry (Project Harbor) to a Helm Chart registry. We'll share some of the key issues we see in Helm Chart management in an enterprise, such as RBAC, signing, vulnerability scanning, and how we provide a integrated user experience in managing/inspecting Helm Charts with docker image management. We'll also discuss the challenges we are seeing in this journey, and the possible solutions.

click here for slide [From Enterprise Image Registry to Chart Repository](https://drive.google.com/open?id=1U3Zs9qkr6eQTHYd8-ze2jbgJI-KMLv11)

**Kubernetes Explained the Easy Way, Using Computer Games... - Steven Trescinski, Gluo**
How do you explain some of the basic Kubernetes constructs (i.e. nodes, pods, rolling updates, image tags, deployments,...) together with their concrete use cases in a fun and memorable way to people that have never heard of Kubernetes before?

The above was the challenge I was faced with when preparing my talk titled "Orchestrating the Container Chaos" for a group of Belgian students. So I started looking for something that most engineering students can relate to...

I ended up modding a first-person shooting computer game to interact with the Kubernetes API to visualise some of the main Kubernetes constructs. During this talk I will explain the tools/technologies used and hopefully inspire others to think outside of the box when preparing for technical talks.
click here for slide [Kubernetes Explained the Easy Way, Using Computer Games...](https://drive.google.com/open?id=1dKeYuBJEnm9SmZjil4aAgVCtOs9D0lZT)

**Upgrading Stateful Sets in Constrained Environment - Kishore Yerrapragada, A10 Networks**

The session will share the experiences we have had and lessons we learned in the process of upgrading micro service based platform with stateful sets in a resource constrained environment.

We have adopted Kubernetes as platform to host as well as distribute our management control plan that manages lots of high through put network software/hardware. We use the same platform to host SaaS as well as ship it on custom hardware to our on premise customers. While Kubernetes allows us to do rolling upgrades with out impacting the availability, we need to make sure our upgrades don't require extra resources as they run on fixed baremetal. These stateful sets include Cassandra, Elastic Search with out shared storage. The session will cover important hurdles in these environments and share some of the techniques we have used to over come those.

**All About Kubernetes Certification Programs - Christopher Hanson, RX-M Enterprises, LLC**

This lightning talk aims to raise awareness about the Kubernetes certification programs: CKA, CKAD, KCSP and CKCP. The discussion will introduce what they are, how they differ from one another, and the value they provide for participating individuals/vendors as well as companies looking to engage a vetted service provider. Attendees will be exposed to resources that will assist them in understanding the paths to certification or conformance as well as the educational and community resources available to test takers for exam preparation.

click here for slide [All About Kubernetes Certification Programs](https://drive.google.com/open?id=1mA9dXm5l8IHe6XGfyBy2zGGWHroMWaqK)

**How to Simplify Data Scientist’s Day in Huge Company Using Kubernetes - Igor Khapov, IBM**

In this presentation, speaker shares his experience on creating Data Science Experience Local based on Kubernetes and how it can accelerate data analysis process. The presenter describes different ways of using docker and Kubernetes for data scientist’s everyday job. IBM uses a cluster environment for internal and external data science projects. We will review all requirements from analytic team to cluster environment to develop, test and manage data science models based on Jupyter, R and Zeppelin notebooks

click here for slide [How to Simplify Data Scientist’s Day in Huge Company Using Kubernetes](https://drive.google.com/open?id=1t7y74abJwKqCEwSprDzv5lpaAs-CVVoT)

**Kubernetes Love Machine Learning, Even on Private Cloud - Hui Luo, VMware**
Kubernetes has established as a good platform for machine learning workloads by extending support of accelerators like GPU, all major public cloud provider are offering GPU enabled Kubernetes services, but public cloud is not the only option for users. There are ongoing efforts from the community to make running machine learning workloads with Kubernetes on private cloud as easy as on public cloud.

This talk is going to cover 3 major challenges that facing private cloud when enable GPU on Kubernetes. I will also demonstrate and discuss some of the projects that help to solve those challenges:
1) Private cloud usually needs to support a wider range of GPU types, in some case, to support heterogeneous GPU in one cluster
2) To support complex hardware topology like RDMA, NVLINK
3) GPU resource contention is usually very high when limited GPU resource shared by multiple teams

click here for slide[Kubernetes Love Machine Learning, Even on Private Cloud](https://drive.google.com/open?id=1kGpN_8_4VEMMGS6q_ETRcY1w31FkthoK)

