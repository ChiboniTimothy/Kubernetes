### Kuberntes Course

- Kubernetes are open source container orchestration tool or frameworks. Kubernetes helps in managing containerized applications in different deployment environments.

 ### Functions of Kubernetes
 - Availability
 - High Performance
 - Scalability
 - Easy recoverey of lost data in case of a disaster

 ### Kubernetes Component

 - Node is a simple server. Node is a worker machine in Kubernetes, part of a cluster.
- Cluster is a set of Nodes that run containerized applications managed by Kubernetes. For this example, and in most common Kubernetes deployments, nodes in the cluster are not part of the public internet.
- Cluster network is a set of links, logical or physical, that facilitate communication within a cluster according to the Kubernetes networking model.
 - Pod is a smallest deployable unit in Kubernetes(K8s). Pods usually run one application container inside it.
 - Pods offer a virtual network and each pod get it's IP address(internal address). When the database container clashes or die a new container will be created and a new IP address will be assigned to it.

 ### Services

 - Service is a permanent IP address which is attached to each pod. Lifecycle of pods and services are not connected in that if a pod dies, the IP address will stay.
 - Service is a load balancer.
 -  Service is a Kubernetes Service that identifies a set of Pods using label selectors. Unless mentioned otherwise, Services are assumed to have virtual IPs only routable within the cluster network.
 - External service is the service which opens communications from external sources. 
 - If we do not want to our databases to be open to the public, we can create internal services. 

## ConfigMap

- A ConfigMap is a type of API object that stores non-confidential data in key-value pairs. ConfigMaps can be used by pods as environment variables, command-line arguments, or configuration files in a disk.
- A ConfigMap allows you to decouple environment-specific configuration from your container images, allowing you to simply port your apps.

### Secret

- A Secret is an object that contains a small amount of sensitive data such as a password, a token, or a key. Such information might otherwise be put in a Pod specification or in a container image. Using a Secret means that you don't need to include confidential data in your application code.

### Volume

- Ephemeral on-disk files in a container offer various issues for non-trivial applications when they are executing in containers. The loss of files when a container crashes is one issue.
- The container is restarted by the kubelet, but in a clean condition. Sharing files between containers operating in a Pod simultaneously presents a second issue. The solution to both of these issues is the Kubernetes volume abstraction. Knowledge of Pods is advised.
   
### Statefulset

- StatefulSet is the workload API object used to manage stateful applications.
- Manages the deployment and scaling of a set of Pods, and provides guarantees about the ordering and uniqueness of these Pods.
- A StatefulSet, like a Deployment, handles Pods that have the same container standard. Unlike a Deployment, a StatefulSet keeps a persistent identity for each of its Pods. These pods are built to the same specifications but are not interchangeable: each has a persistent identity that it keeps throughout any rescheduling.

