# This Repo is to help me document my Revision for Quality Gates

I need to be able to Recall information when asked, therefore good practice is to create a centralised location where information, answers and techniques for responses such as **STAR** are documented.

# Contents
* [STAR Responses :star:](#STAR-Responses)
* [SQL Revision :bar_chart:](SQL_Revision.md)
* [Agile and Scrum](Agile_and_Scrum_Revision.md)
---

# STAR-Responses

## Contents
* [Example](#Example-Question)

1. [Question 1](#Question-1) _**What is Devops**_

2. [Question 2](#Question-2) _**How is DevOps different from agile**_

3. [Question 3](#Question-3) _**What are the different phases of DevOps**_

4. [Question 4](#Question-4)

# Example Question

This section will follow the pattern of **Question** : **Answer**. **STAR :star:** stands for **Situation**, **Task**, **Action** and **Result** and is an extremely useful way of answering a question in an interview. It is a good way to show the employer how you have used, implemented and benefited from a particular tool or software.

**Situation 📋 (S)**: Describe the situation that you were in or the task that you needed to accomplish. You must describe a specific event or situation, not a generalized description of what you have done in the past. Be sure to give enough detail for the interviewer to understand. This situation can be from a previous job, from a volunteer experience, or any relevant event.

**Task 📌 (T)**: What goal were you working toward? 

**Action 👔 (A)**: Describe the actions you took to address the situation with an appropriate amount of detail and keep the focus on **YOU**. What specific steps did you take and what was your particular contribution? Be careful that you don’t describe what the team or group did when talking about a project, but what you actually did. Use the word “I,” not “we” when describing actions.

**Result 💡 (R)**: Describe the outcome of your actions and don’t be shy about taking credit for your behavior. What happened? How did the event end? What did you accomplish? What did you learn? Make sure your answer contains multiple positive results.

Examples Courtesy of [**vawizard**](Documents/STAR_Method_Interviews.pdf)

# Question 1

* **Q** : What is DevOps? 

* **A** : DevOps is of growing importance in the IT industry, it is an approach that aims to synergise the efforts of the development and operations teams to accelerate the delivery of software products, with a minimal failure rate. DevOps Engineers focus on value-added practice, where development and operations engineers join hands throughout the product or service lifecycle, right from the design stage to the point of development. <br>
Devops requires a cultural shift that merges operations with development and demands a linked toolchain of technologies to facilitate collaborative change. Since the DevOps philosphy is at a very nascent stage, application of DevOps as well as the bandwidth required to adapt and collaborate, varies from organisation to organisation. A portfolio of DevOps skills is a very valueable as it shows tools you are familiar with which ould be perfect for an organisation already implementing that toolchain.

**Our ToolChain:**

**Plan** :  App | Software <br>
![Trello](https://img.shields.io/badge/-Trello-026aa7?style=flat&logo=Trello&logoColor=white)

_Communicate with **Team**_ <br>
![Microsoft Teams](https://img.shields.io/badge/-Microsoft%20Teams-6264A7?style=flat&logo=Microsoft%20Teams&logoColor=white)
[![Outlook](https://img.shields.io/badge/-Outlook-0078D4?style=flat&logo=Microsoft-Outlook&logoColor=white)](mailto:jbyrne@spartaglobal.com)

**Code** : Program / Code <br>
[![Github](https://img.shields.io/badge/-Github-000?style=flat&logo=Github&logoColor=white)](https://github.com/JohnByrneJames)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=Git&logoColor=white)

**Build** | **Test** | **Release** <br>
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=Docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/-Jenkins-D24939?style=flat&logo=Jenkins&logoColor=white)

**Deploy** <br>
![AWS](https://img.shields.io/badge/-Amazon%20AWS-232F3E?style=flat&logo=Amazon%20AWS&logoColor=white)
![Ansible](https://img.shields.io/badge/-Ansible-EE0000?style=flat&logo=Ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-623Ce4?style=flat&logo=Terraform&logoColor=white)

**Monitor** <br>
![Splunk](https://img.shields.io/badge/-Splunk-000000?style=flat&logo=Splunk&logoColor=white)

**📋 S** : DevOps is a cultural shift that merges operations with development and demands a collaborative and linked toolchain of technologies to facilitate the change that it brings. During my time at SpartaGlobal we have followed the DevOps process from end to end, The team planned in `Trello` whilst keeping constant communication over `Microsoft teams`, we sent our code to `GitHub` which allowed continuous integration with `Jenkins` finally implementing it on our `deployed` test environment inside `AWS` which when passed was `deployed` to an identical production environment also hosted on `AWS`

**📌 T** : I recieved a webpage designed using `Node`, our aim was to integrate it into a DevOps environment pipeline.

**👔  A** : To create this pipeline known as the **CICD** pipeline incorporating **Continous Integration** and **Continuous Delivery/ Deployment** I first has to connect our GitHub Repository to Jenkins which would automate the process of taking our code, running it through tests in a test environment, and finally take the code integrate it into a final version inside `GitHub` and then deploy it into our production environment. All the environments are standardised to eleminate the potential for technology issues, for example we used **Ubuntu 16.04** and the same version of our technologies, for example **NodeJS 12.0** and **MongoDB 2.3.0**

**💡 R** : This really points out the importance of the DevOps lifecycle, this toolchain helps us as a DevOp automate, test and standerdize the process of developing a software end to end. As a result of this automation I was able to garuntee that the code I push to GitHub is properly tested inside a test environment before ever reaching the point of deployment eliminating the common issue of human error. The ability to integrate code as it is pushed to GitHub totally eliminates the time consuming process of integrating code from multiple contributors at the end of the day.

# Question 2

* **Q** : How is DevOps different from agile methodology? 

* **A** : DevOps is a culture that allows the development and the operations teams to work together. This results in continuous development, testing, integration, and monitoring of the software throughout the lifecycle. <br>
Where as Agile is a software development methodology that focuses on iterative, incremental, small, and rapid releases of software, along with customer feedback. It addresses gaps and conflicts between the customers and developers.

**📋 S** : At SpartaGlobal whilst training to become a DevOps I learnt that DevOps is a culture that allows the development and operations teams to work together, it results in the continous development, testing, integration, and minitoring of the software throughout a software lifecycle. We also used a Kanban board on Trello to plan and track the needs of customers in techniques like the STARFISH, Information Radiators and user-stories. Agile focuses on software development as a methodology in which an iterative, incremental, small and rapid releases of software take place along with customer feedback.

**📌 T** : In the Academy I was given the task to change the front page of a web application.

**👔 A** : To achieve this I set up a continous integration and delivery pipeline which was triggered every time I pushed code to my GitHub Repository. After about 20 seconds of me pushing the code the web page which was live on AWS has the new code deployed into it using the SSH protocol. Using the Kanban board and its agile initative I was able to create the CICD pipeline using the product backlog which allowed me to plan the development of the pipelines setup into weekly sprints. 

**💡 R** : As a result the pipeline was created in a single day, and included every necessary step that was required. The guidance of develop was based on the requirements specified inside the kanban board, this allowed me to stay more on track with what was needed at each stage of development. I was also able to design the pipeline in a way that was appropriate and satisfied the expectations of the tests which were run when it was being testing in the continous integration step. DevOps adds a seamless way to automate the software development process and Agile is a methodology to help track, structure and iterate the development that is happening whilst also thinking about what the customers need in the software.

___

| **Features**                            | **DevOps**                                       | **Agile**                                                  |
|-----------------------------------------|--------------------------------------------------|------------------------------------------------------------|
| **Agility**                             | Agility in both Development & Operations         | Agility in only Development                                |
| **Processes/ Practices**                | Involves processes such as CI, CD, CT, etc.      | Involves practices such as Agile Scrum, Agile Kanban, etc. |
| **Key Focus Area**                      | Timeliness & quality have equal priority         | Timeliness is the main priority                            |
| **Release Cycles/ Development Sprints** | Smaller releases cycles with  immediate feedback | Smaller release cycles                                     |
| **Source of Feedback**                  | Feedback is from self (monitoring tools)         | Feedback is from customers                                 |
| **Scope of Work**                       | Agility & need for Automation                    | Agility only                                               |


# Question 3

* **Q** : What are the different Phases in DevOps? :

* **A** : <br>
  * **Plan** : Initially, there should be a plan for the type of application that needs to be developed. Getting a rough picture of the development process is always a good idea.
  * **Code** : The application is coded as per the end-user requirements. 
  * **Build** : Build the application by integrating various codes formed in previous steps.
  * **Test** : This is the most crucial step of the application development. Test the application and rebuild, if necessary.
  * **Integrate** : Multiple codes from different programmers are integrated into one.
  * **Deploy** : Code is deployed into a cloud environment for further usage. It is ensured that any new changes do not affect the functioning of a high traffic website.
  * **Operate** : Operations are performed on the code if required.
  * **Monitor** : Application performance is monitored. Changes are made to meet the end-user requirements. 

**📋 S** : During my time at SpartaGlobal we practiced the DevOps lifecycle, Starting with Continuous Integration, Delivery and Deployment. The DevOps lifecycle is quite different to traditional lifecycles like waterfall which develop a software by planning, testing, deployment and testing of a software. The difference for DevOps is that it follows an iterative approach of the lifecycle so as well as all these steps being integrated into eachother, they take place week by week to iterably create a software.

**📌 T** : At the academy we were tasked with creating a web app, so I created a Kanban board to help us worth through the process of implementing it into the DevOps Lifecycle.

**👔 A** : To outline the course I took to do this, I first planned using the Kanban board; planning my development needs, acceptance criteria and user requirements. I referred to this a lot and used the SCRUM framework to structure it into weekly sprints. I could push my code to GitHub, using Jenkins it would then be built and deployed into a test environment hosted on AWS, this deployment was tested against some unit tests provided by our trainers. The code was then integrated into our master branch of GitHub if it was successful, and finally deployed into the real-time production environment, available to customers. The production environment is monitored using software like Splunk, this allows me to see traffic activity including need to increase performance or any other maintenance needed on the code.

**💡 R** : The Process from end-to-end of integrating code into production is automated using the DevOps lifecycle and technologies that were available, including **AWS** for hosting, **Jenkins** for Integration and testing and **GitHub** for version control. The process of making a small change is a lot easier using this lifecycle, it also allowed the webapp to have as little downtime as possible as the code is integrated onto code that already exists in the environment, taking 80% less time than if the webapp was taken completely down and added to.

# Question 4

* **Q** : What are the  :