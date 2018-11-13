# kubecon2018-CHINA 
## 11.13 Lightning talk
**Take the Wheel, Don’t Reinvent It! - Deploying Apps With Helm in 5 Minutes - Christopher Hanson, RX-M Enterprises, LL**
So you’ve deployed Kubernetes, now what? Time to deploy your applications! First things first, describe a Deployment to control your Pods--it is probably going to need a Secret or two and maybe a ConfigMap too! Now specify a Service to give it a VIP and introduce an Ingress to expose it! Saving some data? Propose a PVC! What about adding a Service Account or CRB? Lost in alliterations and acronyms? Helm is here to help!

This lighthearted session introduces Helm in an approachable way: revealing its architecture and nomenclature; introducing Charts, Chart components, and the official Charts repository for curated apps; as well as explaining Releases and Release upgrades. Information will be presented in a platform agnostic way to show attendees how to read, customize, and deploy an existing Chart to fit their needs, whether in the cloud, on a given platform or in their own datacenter.
click here for slide [Helm_ckhanson_KubeConChina](https://drive.google.com/open?id=1vW_26CIUKYGc4VZNLL5xPoOQTtedo8Pm)

**From Enterprise Image Registry to Chart Repository - Tan Jiang, VMware**
In the On-Prem enterprise environment, we've been packaging content into docker images and hosting them using docker registry for some time, now helm chart has become the choice of application package format on Kubernetes, it's time to explore what's the proper way to host Helm Charts.

Based on our experience extending a private docker image registry (Project Harbor) to a Helm Chart registry. We'll share some of the key issues we see in Helm Chart management in an enterprise, such as RBAC, signing, vulnerability scanning, and how we provide a integrated user experience in managing/inspecting Helm Charts with docker image management. We'll also discuss the challenges we are seeing in this journey, and the possible solutions.

click here for slide [From Enterprise Image Registry to Chart Repository](https://drive.google.com/open?id=1U3Zs9qkr6eQTHYd8-ze2jbgJI-KMLv11)
