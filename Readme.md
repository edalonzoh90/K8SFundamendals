**1. What is Kubernetes?**  
It's a distributed open-source technology that helps us in scheduling and executing application containers within and across clusters. 

**2. What is a POD?**  
Smallest possible unit (could hold 1 or more containers)

**3. What is a worker node?**  
The computer where the pods run

**4. What is the Proxy in a worker node?**  
Tool to control the network traffic of the pods on the Worker node

**5. What is the Master node?**  
    - It's the control center which interacts with the worker nodes to control them.  
    - It's able to send instructions to a Cloud Provider API to create the resources in the cloud.

**6. What is a cluster?**  
The conjuntion of master node/Worker node/network which connect all differents parts

**7. What is kubelet?**  
It's the comunnication device between the Worker node and the master node

**8. What are the components of a node?**  
    - Kubelet
    - Kube Proxy
    - Docker

**9. What are the components of a Master node?**  
    - Api Server - It's the comunnication device between the Worker node and the master node  
    - Scheduler  
    - Kube-Controller-Manager  
    - Cloud-Controller-Manager

**10. What is kubectl?**  
It's a tool to send instructions to the cluster

## Tools ##
**Minikube**  
Minikube is local Kubernetes, focusing on making it easy to learn and develop for Kubernetes.  
https://minikube.sigs.k8s.io/docs/start/

**Kubernetes**
Installing Kubectl
https://kubernetes.io/docs/tasks/tools/

