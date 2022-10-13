## WHAT IS KUBECTL?

- kubectl is the Kubernetes specific command line tool which lets us communicate and control Kubernetes clusters. 
- Whenever we create, manage, or delete resources on our Kubernetes platform or environment, kubectl is an essential tool.

### WHY DO WE NEED KUBECTL?

- Kubernetes environment or platform is a contained system with a master and worker(user) nodes. 
- The only way to communicate with a kubernate system is through it's system's ```API Server```.
- However, the server is a core component of the kubernates control plane, and it exposes an ```HTTP REST API``` which facilitates communication between users, the cluster and all external compnents. 
- The API is said to be the frontend or main user interface for our kubernates platform.
- Kubectl is a common path to make ```HTTP``` requests to the kubernetes API and it is used to run kubernetes operations, deploy containerized applications, inspect and manage the resouces in our cluster.
It is also used to perform monitoring tasks and viewing the logs of the system.

### KUBERNETES COMMANDS

- Kubectl commands run on a comand line connected to our installed kubernetes on the cloud e.g Google Cloud or Locally.
- Kubectl commands usually follow a specified syntax with commands like ***get, delete and config*** which comes after the declared ```kubectl```.
- The resource types which are being accessed are ```pods```, ```deployments``` or ```services``` and these are followed by the name of the resource if needed.

- Flags modifying the entire command, showcasing location (-f), or port (–port), can be added as necessary.
- The kubectl syntax utilizes this format:

                                        kubectl [command] [TYPE] [NAME] [flags]

- For example, 

                kubectl create namespace ChiboniSpace 
                
- The above command creates a namespace called ```Chibonispace``` and 

                kubectl get pods -o wide    // generates a list of all pods with additional details about each pod.

- If you want to delete a specific pod named 

                sample-pod-0
            
- You can use the command below to delete pods

                kubectl delete pod sample-pod-0 


### INSTALLATION AND SETUP OF KUBERNETES

- kubectl can be installed on your Linux using package installers or curl commands for the latest versions. 
- Some Kubernetes-related software like Docker Desktop or minikube install kubectl on default, so it is important to note which environment our kubectl command is pointed at or configured to. 
- If we want to check this information, we can use ```kubectl config view```. 
- The command above showcases our current Kubernetes configuration (kubeconfig) and the exact kubernetes environment our kubectl command will apply to.
- If we are looking to change the details of our kubernetes configuration, we can use commands like ```kubectl config set-context```, ```kubectl config set-credentials```, and ```kubectl config set-cluster``` to edit the parameters of our ```kubeconfig```. 
- This lets us easily switch the user, namespace, or cluster fields, allowing these parameters to be used by kubectl to communicate with our Kubernetes cluster.

