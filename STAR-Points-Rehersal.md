# STAR-Responses Points

**Help bring up information**

### 1. TMAY

* Games Development, create games: VR, AR, XR, web dev, databases, begin to advanced program.
* Game Dev society/ Final year project

* Something to make an impact on people or current working processes.
* Term DevOps (Research / Friend in Industry) all their innovation
* pursure, no roles, tipoff from career advisor

* 100% entrance exam, Business, SQL, Python and deep dive into DevOps, teamwork with Agile/ SCRUM
* learnt about myself motivated / studious
* ideal environment get stuck in

### 2. CICD Pipeline with Jenkins

* Jenkins is an open source automation server which enables developers to build, test and deploy software.
* Continuous integration is possible with jenkins thanks to its integration capability with version control systems like GitHub
* Continious delivery is met when you produce software that is meets the user-requirements, DOD and any other end goals that are required so it can be released at any time. The last CD is known as continious deployment and is usually looked over as it is typically done manually within the industry due to intricacies of deployment, however it can also be automated with continuous deployment on a live product environment such as EC2 instance running on amazon.
* Use example of Code -> GitHub -> Jenkins (Test & Merge) -> Jenkins (Deploy) -> Put app on EC2 instance -> Available on web

### 3. AWS Networking and Clouds

* **CIDR** Block is the amount of IP addresses, /0 being `16777216 ip` and /32 which is `1 ip`.
* **Monolith** is big, solid and have single point of failure.
* **N-tier** division of system into logical tiers, done with networking, robust, flexiblility and security. Scalable, highly available. DB will usually have main DB that transfers to others if need be, for autoscaling and avoidance of single point of failure. API is intermediary between apps to swap information.
* **VPC** is a virtual private cloud, following N-Tier it is a service provided by Amazon and allows you to create a secure network with a seperation of representation and data layers, leading to higher security.
	* Key Words:
	* **IGW** 
	* **Subnet** Internal network inside a VPC
	* **NACLs** Network access list; firewall at level of subnet; deny IP as well as allow it. Restrict access to private subnet with this. Filter Incoming and outgoing traffic.
	* **SG** Security group; firewall at instance level. filter incoming traffic.
	* **Route tables** contains routes that will control traffic flow. Set route to pub subnet with IGW attached.
	* **EC2** Elastic Compute Cloud
	* **Avail-zones** are logically connected but physically segregated data-centers inside a region.
	* **Epheremal ports** short lived TCP port from the client, specific OS use different port range and use it to recieve a request back after a request.
	* **Bastion server** special purpose machine, specifically designed to withstand attacks and allows access into our DB in the private network. It removes all access/ services to reduce attacks.
	* **Load Balancer** efficienty distributing incoming across group of backend servers to even share workload.
		* **Benefits**
		1. Highly available
		2. Secure
		3. Elastic
		4. Flexible
		5. Robust
		6. Hybrid 
		7. Remove need to manually upgrade hardware!!
	* **Auto-Scaling** adjusts capacity of machines/ servers to maintain optimal performance whilst keep the costs at a minimum. Scaling up and down entails hardware allocation, such as bigger processor or storage and scaling out entails running up more instances of a single server/ machine.
		* **Benefits**
		1. Reduced Downtime
		2. Scalable
		3. Remove Redundancy - [2 load balancers to monitor eachother to look after clusters overall health]
		3. Flexibility
		4. Efficiency
		5. Global Server Load Balanced
		6. Avoid Single point of failure
	* **AMI** Amazon Machine Image, Provides info to launch instance on demand, can be used to launch multiple identical instances (scaling out)
	* **Hybrid Cloud** When a company uses both on prem and cloud architecture in a business model, typically allowing the organisation to store confidential data on prem and publicly available data and info on a cloud service like AWS.
	* **Multi-Cloud** A organisation that splits their infrastructure across multiple cloud providers/ regions to reduce the risk of failure. These all communicate with eachother using things like Route 53 which can divert traffic even across to other providers/ regions.
	* **Route 53** A DNS failover service that aids in the availability of a service, to route users to a different service if one fails, to practically hide any issues you are having to the customers. <br> Amazon Route 53 is a highly available and scalable cloud DNS web service. It is designed to allow developers to control the flow of traffic into an application, including triggering disaster recovery plans that will redirect users to another location if something happens on one location.
		* **benefits**
		1. Highly available
		2. reliable
		3. Fliexible
		4. Designed for use with other AWS services
		5. Simple
		6. Fast
		7. Cost-effective
		8. Scalable and simplfication of hybrid cloud

### 4. Configuration Management Tool (Ansible) | IAC and Orchestration tool for creating network infrastructure using Terraform.

* **Configuration Management tool Ansible**
	* Use playbook to automate provisioning of instances
	* Managable through playbooks, easy to test before officially runnin with `check`
	* **Benefits**
		* Simple
		* Agentless, doesn't need a agent on servers to configure - only a single controller server.
		* IT automation tool, to avoid manual provisioning and do multiple servers all automatically.
		* Is is relatively simple to use and allows SSH to securely provision the servers.
		* Power to configure the hybrid cloud, within any cloud provider and on prem locations.
		* Save time in terms of testing servers remotely from ansible controller
		* Open source software
		* Makes it configuration management predicatable (cost-effective)
		* automate process...
	* **Ad-hoc** Commands are one line commands use to retrieve data quickly and efficiently; useful for retrieving data about the servers/ region such as space left or time.
	* **YAML** ansible-playbooks are written in YAML or YML, which help install/ update programs. Automate tasks across multiple servers, it works on indentation like python.
	* Can configure cloud servers in minutes thanks to playbooks and SSH connections, using keys that allow access. The secret and private keys allowing it to log in using your user account.
	* The growing predominance of multi-cloud and hybrid cloud architectures Ansible provides a common platform for enabling mature DevOps and infrastructure as code practices. Ansible is easily integrated with higher-level orchestration systems, such as AWS Code-Build, Jenkins, or Red Hat.

* **IAC Orchestration with Terraform**
	* Uses declerative configuration langauge known as HCL, or JSON.
	* **Cloud Agnostic**, can create complex infrastructure onto cloud services regardless of what service it is. Typically a couple of lines can be changed to perform the same infrastrcture feat on another provider.
	* **Statefull** keeps a local state file that tells itself what infrastructure has already been created. This allows immutable infrastructure to exist as if it is deleted then it will be recreated using the same credentials as it is has been stored locally.
	* **Open-soruce and self-hosted** it is self-hosted and doesn't need much configuration to get it up and running and is open source so allows lots of providers such as AWS to integrate their cloud service into it as they have.
	* **IAC** is a direct solution ot **Manual provisioning**
	* Configure remotely from on prem into the cloud allowing you to keep your infrastructure on prem and secure.


# Four Pillars of DevOps

### **Ease of Use**
### **Flexibility**
### **Robustness**
### **FAST** / **COST**

* FLEXIBLE, ROBUST, EASE OF USE and AUTOMATED
* SECURITY SKILLS
* COLlABORATION AND TEAMWORK
* SCRIPTING SKILLS
* DECISION MAKING
* INFRASTRUCTURE KNOWLEDGE
* SOFT SKILLS, TEAMWORK, GOOD COMMUNICATION AND OVERALL MARKET/ INDUSTRY KNOWLEDGE
