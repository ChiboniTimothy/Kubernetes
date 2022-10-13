## DevOps with Python

- DevOps helps in deploying and hosting python apploications. DevOps as a process necessitates some amount of Python coding to make sure that putting its concepts into practice produces the best possible outcome. Python is a great tool for DevOps for offers the flexibility and accessibility required in this procedure. It gives DevOps professionals improved, straightforward, yet complex custom utilities to design, test, deploy, visualize, and monitor the DevOps lifecycle.

### What is DevOps?

- The combination of software development and operations is known as DevOps.
With this technique, a single team can manage every stage of the lifetime of an application, from development to testing to deployment and operations.
System administrators, QA engineers, and software developers may communicate more effectively thanks to DevOps. 

![DevOps](./DevOps.jpeg)

### Why Python for DevOps

- Python plays a significant role in DevOps. Majority of DevOps teams utilize Python as one of their key technologies becuase with Python anythng can be done in DevOps.
- Automation is the major area that requires python in DevOps. Python makes it easy to automate the CI/CD pipelines.
- Python is very important for DevOps because the scripting language make it simple for automations of the DevOps life cycle management. DevOps teams use Python to automate the configuration management and infrastructure deployments. Python is a perfect choice for DevOps jobs because of its adaptability and accessibility, allowing the entire team to create web applications, data visualizations, and to enhance their workflow with personalized utilities.
- The scripting language is utimately used for modifyication, automation and configuration of tools used in DevOps like CI/CD pipeline automations. Additionally, Python can be used for automating small daily checking and monitoring tasks, and also automate the operational tasks which are repetitive and periodic such as system admins.
- Python is an essential component of the entire DevOps cycle and general culture because it is so versatile and effective. It is also used to govern or was used to write popular DevOps tools like Ansible and Saltstack. 
- Python is utilized for full infrastructure automation and orchestration; its ability to code and debug puts it miles ahead of Ruby in this regard.

     
### SYSTEM ADMINITRATIONS

- System administration is a branch of engineering that focuses on the operational control of human-computer systems and treats both the technology and the users of the technology equally. You are referring to the hardware, system users, and system software when you say that a system is a collection of interconnected pieces that are connected in accordance with a plan to carry out a certain purpose. In contrast to adding and configuring new workstations, creating user accounts, or installing system-wide software, system administration is more concerned with planning and building an efficient network of computers so that actual users may perform their responsibilities.

### WHY SYSTEM ADMINISTRATION

- It is the duty of system administrators to logically and efficiently designing the network, installing a large number of easily upgradeable devices, determining what services are required, planning and executing necessary security, and creating a comfortable environment for users. In light of the foregoing, a working knowledge of data flow across machines is necessary for the system administrator, as is a knowledge of how each computer impacts the others. A basic understanding of computer programming is helpful for system administrators in today's society.

### KUBERNETES

- Kubernetes is an open source solution to deploy, scale, and manage containerized applications everywhere. It is also sometimes abbreviated as K8s, with the 8 denoting the number of letters between the ```"K"``` and the ```"s."```

- Kubernetes streamlines application management by automating operational activities associated with container management and providing built-in commands for application deployment, rollout of updates, scaling up and down to accommodate changing requirements, monitoring, and more.

### BENEFITS OF KUBERNETES

- Kubernetes has several benefits, which are listed below.

1. Automated operations

- Kubernetes has built-in commands to handle a lot of the heavy lifting that goes into application management, allowing us to automate day-to-day operations. We can ensure that applications always run as intended to.

2.  Infrastructure abstraction

- Kubernetes manages the computation, networking, and storage on behalf of our workloads after installation. Kuberntes allow us to concentrate on applications rather than the underlying environment. 

3. Service health monitoring

- Kubernetes performs ongoing health checks on our services, restarting any that fail or stall, and only make users aware of the services after it has determined that they are up and running. 

### USE OF KUBERNETES

- Applications that are simple to manage and deploy anywhere are made using Kubernetes.
- Kubernetes provides us with a selection of solutions to suit our needs when it is made available as a managed service.
- Below are use of Kubernetes.

1. Increase in development velocity

- Kubernetes enables us to create cloud-native microservices-based applications. It also supports containerization of existing apps, making it the foundation of application modernization and allowing you to develop apps more quickly.

2. Deployment of Applications

- Kubernetes are designed to be used anywhere, allowing us to run our applications on-premises, in public clouds, or in hybrid deployments. As a result, we can run our applications wherever we need them.

3. maintaining effective services

- The size of a cluster necessary to run a service can be adjusted automatically by Kubernetes. This gives us the ability to run our applications effectively and automatically scale them up or down based on demand.

### CLOUD

- The term cloud refers to a global network of servers, each with a distinct function. The cloud is not a physical entity, but rather a vast network of remote servers located all over the world that are linked together and intended to function as a single ecosystem. These servers are intended to store and manage data, run applications, or provide content or services such as streaming videos, web mail, office productivity software, or social media. Instead of accessing files and data from a local or personal computer, you access them online from any Internet-capable device—the information is accessible wherever you go and whenever you need it.

### IMPORTANCE OF CLOUD 

- Computation and storage occur on servers in a data center rather than locally on the user device, users can access the same files and programs from nearly any device using the cloud. This is the reason why a person may log into their Instagram account on a new phone after their old phone breaks and still find their previous account, with all their photographs, videos, and chat history, there. The same principles apply to cloud storage services like Dropbox or Google Drive as well as cloud email providers like Gmail or Microsoft Office 365.

### TYPES OF CLOUD DEPLOYMENT

- There are four ways to deploy cloud resources. 

1. Public Cloud 

- is the type of cloud which shares resources and provides services to the public over the Internet. A public cloud is a service provided by a third party and may contain servers located in one or more data centers.

2. Private Cloud

- this is a type of cloud which is not shared and provides services over a private internal network typically hosted on-premises.

3. Hybrid Cloud

- is the type of cloud which shares services between public and private clouds depending on their purpose. A business may utilize its private cloud for some services and the public cloud for others, or it may use the public cloud as a backup for its private cloud. 

4. Multi-cloud

- A multi-cloud deployment is one that makes use of several different public clouds. With a multi-cloud deployment, an organization essentially leases virtual servers and services from various outside providers; to continue the comparison from earlier, this is similar to renting out numerous nearby plots of land from various landlords. Hybrid clouds can be deployed across many clouds, and vice versa.

### GITOps

- GitOps is an operational framework that incorporates DevOps best practices for infrastructure automation, including version control, collaboration, compliance, and CI/CD tooling, which are often used for application development.
- Three essential elements are needed for GitOps:
           
           DevOps **GitOps** = IaC + MRs + CI/CD 

1. IaC: 

- GitOps defines infrastructure using a Git repository as the single source of truth. A Git repository is a .git folder in a project that tracks all changes made to files in a project over time. Git is an open source version control system that tracks code management changes. The concept of storing all infrastructure configuration as code is known as infrastructure as code (IaC). The actual desired state may or may not be coded (e.g., number of replicas or pods).

2. MRs: 

- GitOps employs merge requests (MRs) as the change mechanism for all infrastructure updates. The MR is where teams can collaborate through reviews and comments, as well as where formal approvals take happen. A merge commits to your main (or trunk) branch and acts as an audit log.

3. CI/CD: 

- GitOps uses a Git workflow to automate infrastructure upgrades with continuous integration (CI) and continuous delivery (CI/CD). When new code is integrated, the CI/CD pipeline updates the environment. GitOps automation overwrites any configuration drift, such as human modifications or errors, so that the environment converges on the desired state stated in Git. GitLab manages and implements GitOps automation using CI/CD pipelines, although other forms of automation, such as defines operators, can also be utilized.

### BENEFITS OF GitOps

- GitOps offers a variety of benefits, such as increased productivity and security, lower costs, and quicker deployments.
- GitOps enable Organizations to use a single, integrated tool to manage the complete infrastructure and application development lifecycle. This enables better team cooperation and communication, which reduces errors and speeds up problem solving. Additionally, GitOps enables businesses to benefit from the most recent DevOps techniques and equipment, such as containerization and microservices.