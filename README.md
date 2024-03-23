* WHAT IS KUBERNETES

1) Kubernetes is a portable, extensible, open source platform for managing containerized workloads and services, that facilitates both declarative configuration and automation. It has a large, rapidly growing ecosystem. Kubernetes services, support, and tools are widely available.

2) The name Kubernetes originates from Greek, meaning helmsman or pilot. K8s as an abbreviation results from counting the eight letters between the "K" and the "s". Google open-sourced the Kubernetes project in 2014. Kubernetes combines over 15 years of Google's experience running production workloads at scale with best-of-breed ideas and practices from the community.



* WHY USED KUBERNETES

Kubernetes can be used to deploy and manage a wide range of applications, including web applications, big data, and machine learning applications. It has features such as scaling, orchestration, and resource management that make it easy to deploy and manage complex applications.

Kubernetes is a platform that can help manage containerized applications at scale. It has many benefits, including:


1) Improved scalability :
Kubernetes can automatically scale up or down to meet demand, such as when there are spikes in CPU usage or memory.
High availability: Kubernetes can help keep applications running despite challenges like failed servers, crashed containers, and traffic spikes.


2) Resource efficiency :
Kubernetes can help optimize hardware usage.


3) Self-healing capabilities :
Kubernetes can perform health checks and enable application self-healing.


4) Portability :
Kubernetes can be used across on-premises and cloud environments, making it easy to move applications between different cloud providers or data centers.


5) Support for DevOps, Cloud, and DevSecOps practices :
Kubernetes can help businesses manage IT workloads efficiently by grouping software into a container cluster that runs on a virtualized host OS.




* HOW DOES KUBERNETES WORK

1) Kubernetes is an open-source platform that uses pods and services to create networking. A pod is a group of one or more containers that share a network namespace and IP address. Containers within a pod can communicate with each other using localhost, which simplifies port management and container communication.
   
2) Kubernetes also uses services to expose one or more pods to the outside world. Services are implemented as load balancers, which can load balance traffic across multiple pods.
   


-Here's how Kubernetes works:
  
1) Networking :
Kubernetes creates pods and services.

2) Resource provisioning :
Kubernetes abstracts machine resources and presents them to workloads using API objects.

3) Pattern :
Kubernetes follows a client-server pattern, with server machines called master nodes and client machines called worker nodes.

4) Pods :
Each pod is assigned a unique IP address.

5) Containers :
Containers within a pod share the same network namespace, meaning they can communicate with each other using localhost.

6) Nodes :
Physical or virtual machines that exist between the pod and cluster, host the pods.

7) Control plane :
The control plane is the orchestration layer, which acts as the communications director for a Kubernetes cluster.

8) Cluster : 
A Kubernetes cluster is a group of nodes that run containerized applications, together with a control plane.

