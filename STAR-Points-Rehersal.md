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
		* Benefits
		1. Reduced Downtime
		2. Scalable
		3. Remove Redundancy - [2 load balancers to monitor eachother to look after clusters overall health]
		3. Flexibility
		4. Efficiency
		5. Global Server Load Balanced
	* **AMI** Amazon Machine Image, Provides info to launch instance on demand, can be used to launch multiple identical instances (scaling out)



# Four Pillars of DevOps

### **Ease of Use**
### **Flexibility**
### **Robustness**
### **Cost**

### FLEXIBLE, ROBUST, EASE OF USE and AUTOMATED
### SECURITY SKILLS
### COLlABORATION AND TEAMWORK
### SCRIPTING SKILLS
### DECISION MAKING
### INFRASTRUCTURE KNOWLEDGE
### SOFT SKILLS, TEAMWORK, GOOD COMMUNICATION AND OVERALL MARKET/ INDUSTRY KNOWLEDGE
