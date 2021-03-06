## 11.14 Keynote Sessions
- - - 

**Deep Customized Kubernetes for Machine Learning in Tencent - Shengbo Song, Tencent**

*keywords* **GaiaStack,custom Kubernetes,** 

sharing sigle GPU：
- VMs use NVIDIA GRID, not suitable for runc.
- Processes use MPS Service, CONs:hard resource limits 

exp: 如何申请GPU服务？GPU池化已经作为服务使用了吗？

The Kubernetes and Tensorflow are playing an important role in machine learning, However, the original Kubernetes doesn't serve machine learning well, lacks of accurate GPU scheduling policy, GPU topology awareness and resource limitation etc. In this presentation, we will review recent events about machine learning in Kubernetes community, give us a overview of what changes have been made to Kubernetes to support machine learning in Tencent, the challenges it faces, and look forward to how to address the challenges.

download PPT [Deep Customized Kubernetes for Machine Learning in Tencent](https://drive.google.com/open?id=1tG9xNGbjU-2yP4bBMuTDWRIkURn3-_8t)

- - - 
**A Day in the Life of a Data Scientist. Conquer ML Lifecycle on Kubernetes - Rita Zhang & Brian Redmond, Microsoft** 

*keywords* **kubeflow** 

Ever wondered how machine learning models are built? Well, here’s your opportunity to come spend a day in the life of a data scientist. This will be a practical guide to the day-to-day lifecycle of a machine learning model. Dive end-to-end through code collaboration, dataset preparation, training and serving. We will cover how to utilize open source tools like Kubeflow and offer an in-depth view of how they operate and aide the machine learning development lifecycle. This session is for both data scientists and infrastructure/SRE teams alike helping bring the benefits of DevOps to AI and machine learning.

download PPT [A Day in the Life of a Data Scientist](https://drive.google.com/open?id=1kamfTvH4WqYeQLam0DvlwWHO2yavDItn)

- - - 
**Serverless Kubernetes Boosts AI Business - Jian Huang, Huawei**

*keyword* **kubeflow,serverless，GPU sharing**

Kubernetes is becoming more and more popular in IT systems including running the AI workloads. Currently, ML/DL Services of Huawei cloud are running over Kubernetes clusters.

In order to make the AI services focus on their business without caring the underlayer infrastructure like physical machines and GPU offering. We provide the serverless Kubernetes services(CCI) in order to meet their requirements. And serverless Kubernetes is very suitable for the users to run the short-time jobs.

In this session, we try to introduce the effort we have make on this area. Such as use kata container to protect the container's security so multi-tenant's workload can run on the same physical machine; support AI jobs with multiple devices like Nvidia GPU, InfiniBand; experience of running DL frameworks like tensorflow over Kubernetes in Huawei and so on.

download PPT [Serverless Kubernetes Boosts AI Business](https://drive.google.com/open?id=1ChLe_LrVKDW9ItJaiHb0GxjFmEI1Ix1s)

- - -
**Flowkube: GPU Resource Management On JDOS - Liang Yongqing, JD.com**

*keyword* **kubeflow,serverless**

Flowkube is a service we developed to manage our GPU Resource. It contains:
1.      GPU machine management: install, driver,manage cordon, zone, label ,etc  
2.      Builtin CI system ,User don't need to build their own docker image
3.      Support our ContainerFS system: store training resource ,and training log
4.      TensorFlow training base on Kubeflow
5.      One-Click Serving After training
6.      A Realtime Gpu usage monitor
7.      A Billing system to account all the department ‘s usage

[Flowkube: GPU Resource Management On JDOS](https://drive.google.com/open?id=1_KyeKjKLhlToVjvKCx-UWXF8dk8M4JRz)

- - -
**Kubernetes Native DevOps Practice - Lei Wang, TenxCloud**

This topic will cover a new approach that we used to build DevOps solution on top of Kubernetes. We find it's quite easy to setup, use and maintain, it can also leverage lots of existing features from PaaS if we're building both. Here is the agenda:
1. Our DevOps Expectations - Easy to use/scale/extend; high availability; a superset, can integrate with existing CI/CD tools
2. Kubernetes capabilities and advantages to build DevOps solution - Pod/Job/CrontJob/InitContainer/Resource management/Scheduling
3. Architecture and features
 - CRD and operator design
 - Pipeline/Stage/Task/Task Template/Version Control/UI generation/Volume...
 - Logging, monitoring, autoscaling, high availability
 - Extensibility/Integration
 - CI/CD examples
4. Future plan - ChatOps/AIOps - Enterprise users are actively using this solution, bring consistent user experience and generate consistent system metrics, make DevOps easier.

download PPT [Kubernetes Native DevOps Practice](https://drive.google.com/open?id=1YIF-KJpBywdR4NayPbigi2TCwdB2vJz_)

- - -
**Mesher: The Practice of a Production-Level Service Mesh - Xiaoliang Tian, Huawei**

2018 is the year of service mesh, Mesher is an open source project of service mesh implementation. Mesher is flexible and open, it is able to run on any infrastructure or platform like kubernetes. By extending plugins, Mesher can be easily integrated with various protocols and backends including Prometheus, zipkin etc..

In this topic, Xiaoliang will share his practice about the implementation of a high performance service mesh, how developer use service mesh in their production environment and how Mesher and micro service framework use unified Istio control plane to connect to each other.

download PPT [Mesher: The Practice of a Production-Level Service Mesh](https://drive.google.com/open?id=1RYhFiWNsJdmMtDFEwszYRzH3kmfi1qmq)

- - - 
**Benchmarking Machine Learning Workloads on Kubeflow - Xinyuan Huang, Cisco Systems, Inc. & Ce Gao, Caicloud**

Benchmarking is an essential part in machine learning research and productization, that provides useful performance information from the perspectives of both models and systems. While Kubernetes and Kubeflow give us a great platform for ML workloads to run on, they do not automatically provide a straightforward way to perform benchmark tasks, especially for complex ML workloads based on distributed jobs. In this talk we present Kubebench, an open sourced benchmarking tool based on Kubeflow, that helps us better understand the performance signature of our ML workloads on Kubernetes through automated and consistent benchmarks. We also show how we can leverage other benchmarking efforts from academia and industry like MLPerf and Dawnbench.

download PPT [Benchmarking Machine Learning Workloads on Kubeflow](https://drive.google.com/open?id=1eDha39pBwYBIN8mnWYhEH9doNpIlBaJY)