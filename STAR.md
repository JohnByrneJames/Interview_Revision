# STAR-Responses

## Contents
* [Example](#Example-Question)

* [_**TMAY**_ A.K.A **"** Tell me about yourself... **"**](#TMAY)

1. [Question 1](#Question-1) | _**What is Devops**_

2. [Question 2](#Question-2) | _**How is DevOps different from Agile**_

3. [Question 3](#Question-3) | _**What are the different phases of DevOps**_

4. [Question 4](#Question-4) | _**Difference between Agile and SCRUM**_

5. [Question 5](#Question-5) | _**What is the benefit of Using a cloud service like AWS?**_

# TMAY

* **Q** : Tell me about yourself

* **A** : Of course!, Hi I am John Byrne; its a pleasure to meet you. I'm a recent graduate from the University of Greenwich where I studied Computing with Games Development. During my time on the course I was able to create several games that I was especially proud of using up and coming technologies such as VR, AR and XR. I also worked on web development using ASP.NET, PHP, CSS, HTML and bootstrap, as well as relational databases in oracle and beginner to advanced programming in C# and C++. I really enjoyed developing games, so I joined the Games Development society where I worked with my fellow students to work on C# skills and projects out of class hours, it was a lot of fun and I learned a lot about myself. For the final year project I chose a very impactful topic that was VR in education, I developed a Virtual Reality game that was designed to help junior ophthalmologists train in a safe, secure and cost-effective environment. I finally graduated with a 1st class degree.

This made me think about the kind of industry I want to go into after I graduated, I wanted to do something that not only did I enjoy thoroughly but also made an impact on people. After some research I came across the term "DevOps", I looked at the all the innovation that created this term and how it affected any organisation that adopted it. I made a decision to pursue this idea and the more I looked into it the more excited I became. I started looking into opportunities for graduates but they were practically impossible to find, after that I asked a career advisor in my University who referred to me Sparta Global as a potential trainer. 

I joined in April after I got 100% in the entrance exam, and during my time here so far not only have we covered Python, SQL, and dove deep into the world DevOps using automation tools, automating infrastructure, working as a team with our Agile methodology and SCRUM framework but I have also learnt alot about myself. I am a motivated and very studious individual who is hungry to learn and develop skills where ever possible; the academy has created an ideal environment for me to get stuck into these technologies and widen my breadth of knowledge. I am looking forward to what the future holds, I want to learn as much as I can and put it into action in a company! So thats me; Thanks for listening.

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

**👔 A** : To achieve this I set up a continous integration and delivery pipeline which was triggered every time I pushed code to my GitHub Repository. After about 20 seconds of me pushing the code the web page which was live on AWS has the new code deployed into it using the SSH protocol. Using the Kanban board and its agile initative I was able to create the CICD pipeline using the product backlog which allowed me to plan the development of the pipelines setup into steps. 

**💡 R** : As a result the pipeline was created in a single day, and included every necessary step that was required. The development was guided on the requirements specified inside the kanban board, this allowed me to stay more on track with what was needed at each stage of development. I was also able to design the pipeline in a way that was appropriate and satisfied the expectations of the tests which were run when it was being testing in the continous integration step. DevOps adds a seamless way to automate the software development process and Agile is a methodology to help track, structure and iterate the development that is happening whilst also thinking about what the customers need in the software.

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

* **Q** : Difference between Agile and SCRUM?

* **A** : The key difference is that Agile is a software development methodology whilst SCRUM is a framework put in place to aid in the agile approach. 

Agile is a practice that helps continuous iteration of development and testing using the System Development Lifecycle process. Agile breaks the product into smaller builds, it also encourages the activites such as testing and development to take place concurrently unlike a lot of other software development methodologies. Furthermore, due to the iterative nature of Agile it encourages teamwork and constant interaction with stakeholders; particularly the product owner who provides constant feedback on progress. The development process is able to then incorporate these changes as the project continuous, which is the main benefit of the agile methodology. This means the end-product is more likely to be suited towards the product-owners expectations, in efficiency, functionality and most-likely bug free due to the constant testing that takes place at every step.

SCRUM is agile process or framework that allows the team to focus on delivering the business value in the shortest time, it rapidly and repeatably insepcts actual working software. It constantly emphasizes accountability, teamwork, and iteartive progress towards a well-defined goal. A key value that comes from using the SCRUM framework is its ability to adapt where requirements are likely to change or most of the time not known as the start of the project. As the project is done in iterations and encourages face-to-face communication it is far-easier to decide where and when a new requirement should be incorporated into the project using SCRUM EVENTS and SCRUM ARTIFACTS.

**Key Difference**
* _Agile is a continuous iteration of development and testing in the software development process whereas SCRUM is an agile process to focus deliverying the business value in the shorted time._
* _Agile methodology delivers the software on a regular basis for feedback while SCRUM delivers the software after each sprint._
* _In the Agile process, leadership plays a vital role; on the other hand, SCRUM fosters self-organizating, cross functional teams.
* _Agile involves collaborations and face-to-face interactions between members of various cross-functional teams whereas SCRUM collaboration 
is achieved in daily stand ups_
* _In Agile process design and execution should be kept simple whereas in SCRUM process design and execution can be innovative and experiemental_

**📋 S** : Agile is a software development methodology that helps continuous iteration of concurrent testing and development of software, generally using the SDLC process. The agile approach encourages self-organising and cross-functional teams as well as constant communication with stakeholders, particularly the product owner so he can be involved throughout the process and aid in bettering the software at every iteration to better meet the end-users needs. On the other hand SCRUM is a agile framework that allows the team to focus on delivering the business value in the shortest time. There are 4 key principles that come with the framework these are; Individuals over processes and tools, working software over documentation, customer collaboration over contract negotiation and responding to change over following a plan. Teamwork, accountability and iterative progress towards a well-defined goal is what SCRUM is all about, it encourages face-to-face communication through SCRUM events like a Standup or Sprint review, and progress through sprints and the product backlog. A key value that comes from the SCRUM framework is its ability to adapt to ever-chaning requirements as, a lot of projects do not have their required pre-defined at the start of a project.

**📌 T** : I had been the set task of creating an Airport program that was able to book flights for passengers and also add new flights to the list of existing flights.

**👔 A** : To help structure our work I created a Kanban board using a popular sight called Trello, this 

**💡 R** :

# Question 5

* **Q** : What is the benefit of Using a cloud service like AWS?

* **A** : 

**📋 S** : To understand the concept of cloud you need to know the difference between the cloud and on-prem; as its called in the business. On-Premises or On-Prem defines infrastructure such as server on the business site, so in a building they own for example, whereas the cloud defines a location that is simply not on that companies premises it is perhaps in a amazon warehouse somewhere but it is available as a service. This allows the company to store their data on a server hosted on the cloud, therefore they don't need to worry about the intracicies of security, hardware or maintenance as it is done by the provider; in this case Amazon.

**📌 T** : We were set the task of creating what is known as an Ansible controller, this controller should be able to create a EC2 instance on AWS using a playbook and then be able to provision via a second playbook which would gain access to this instance via SSH secure entry. Once inside the playbook would run an provision our web server.

**👔 A** : To do this we were going to have to make use of a concept known as the hybrid cloud, this is a cloud that consists of both on and off prem data being shared, accessed to communicated from a companies premises to the cloud. Using Vagrant a software to building and maintaining virtual software; I created a ansible controller inside a VM on my local machine, I then used Ansible a configuration management tool to communicate with AWS using some credentials and a playbook to instruct AWS to create a EC2 instance from a previously created AWS AMI which, once this was created I then had ansible go into this machine and provision so it had the necessary pre-requisities to run the NGINX server and a node app the playbook had copied over. 

**💡 R** : Within a couple of minutes I was able to deploy a web app to the cloud onto a EC2 instance, the whole process had been automated and could achieved all from a centralised location on prem. Not only does save money as the cloud is generally a cheaper solution that multiple on prem data-centers, but it also hands of the job of maintenance of these servers, and the cloud is also capable of making this app available in multiple regions within minutes due to its global presence around the world making it highly available. Not to mention hundreds of micro-services that can control the size of your applications in response to demand adding scalability, consequently eliminating any single point of failure. More on this though with the introduction of docker and kubernetes a containerization and container orchestration system.

# Question 6

* **Q** : What does an API do?

* **A** : 

**📋 S** : An API, also known as an Application programming interface is software intermediary, that allows two applications to talk to each other. Typically it respondes to a HTTP request made either by a search; for example clicking the Booking.com page will make a request to their servers to retrieve and load the appropriate information to display on their home page, the API will get that information pass it into your browser who will kindly display it for you. It can also be done via a programming language, such as the powerful python, which uses the requests module to make HTTP requests to an API, regarding either headers or contents; the API will respond with a status code, 200 being success, 404 being nothing found and 500 being a server error. There are lots more but theses are the most common. If you do get a success the contents of the request are usually recieved in the form of a JSON file, relative to a dictionary in python. An API is something that can accomplish a singluar task very quick, with high accuracy and reusability.

**📌 T** : I was set the task of retrieving and displaying some data from any API of my choice, as long as it displayed the benefit, speed and usefulness of the API itself.

**👔 A** : To do this I first created a class in python, this class would be called whenever I got a status code response from which API I was calling; if the status code was not 200 for any reason, the class would stop my API call and let me know that it had failed. The next step was to actually get an API I wanted to request information from; I am a big fan of pokemon and managed to get a pokemon API with a correlating access Key, I made a request to the server using the API string which is a URL with some variables in it, I simply changed the variable pokemon to equal "pikachu", this made a request to the pokemon servers and returned a rather large JSON file with everything I could ever want to know about the pokemon pikachu.

**💡 R** : APIs are the middle man between applications, they help applications pass information that is required and display it where necessary. They can also be very reusable as they return the content in a format that can easily be turned into a dictionary in python for example allowing very easy access of that information. APIs can efficently distribute content, allow personalisation for different audiences and most importantly are an automated solution to managing the interface that returns the data.

# Question 7

* **Q** : How have you worked with Databases?

* **A** : 

**📋 S** : First of all I'd like to give a quick overview of what my database knowledge and experience consists of. SQL or Structured Query Language is a universal database querying language, it allows the creation of tables, databases, relationships as well as addition of data into those tables. Although there are many different database management systems such as Oracle, MongoDB, MySQL and SQLServer the syntax between them varies only slightly. Databases are ideal places to store data as they retain data integrity, accessibility and security through good design; such as relational databases. A relational database allows a relationship between two or more tables to define the access of data, therefore allowing more accurate querying of information. Relationships between two rows in a table can be made using unique identifers known as keys, a foreign key is data defined in a row that links back to its own primary key in another table; linking the two rows.

**📌 T** : In the SQL project, I worked with the Northwind database a sample relational database available from microsoft. I had to use the skills I had learnt in the last week to gather data on suppliers who had sold more than $10,000 worth of stock.

**👔 A** : To do that the first thing I did was to SELECT the appropriate tables, and then use inner joins to compare them to eachother so I could query them as a whole. I also used the filtering function ORDER BY to order it by the highest grossing company.

**💡 R** : As the table was designed using normal form, a guide used to create a acceptable relationship diagram I was able to retrieve the data I wanted defining the tables and then manipulating that data in the way I needed, in this case to show the highest earning suppliers, that are earning over $10,000. This makes it both easy and efficient as the data is stored in a way that allows it to be accessed easily through querys, then it can be put into a chart or table to visually display the output for a business for example. SQL is a great and powerful data language, it doesn't require a lot of know how to produce useful data sets from a database and it does it all at very fast.

# Question 8

* **A** : What are the benefits of OOP compared to functional programming.

**📋 S** : OOP or Object oriented programming and Functional programming are programming paridigms in which a program is designed in different ways; first of all OOP is a paradigm based on the concept of "objects", which may contain data in the form of procedures, often known as methods. Objects are capable of accessing and modifying the data fields of which they are associated with key words such as "this" or "self", essentially altering the state of that object. Functional program focuses on the concept of pure programming, this means a function should return a result purely using the value that was based in, all objects created in functional programming are also totally immutable; among other differences such as the ability to allow any order of execution and addition of parallel programming.

**📌 T** : During the academy I was given the task to create a program that made use of the OOP concept of inheritance, to help me understand the concept I decided to create a base class known as vehcile and demonstrate inheritance through further parent classes which inherited all of its attributes along with any additional attributes that class needed.

**👔 A** : To do this I first created a class, sometimes referred as an object; the base of all object oriented programming, it has its own set of attributes and methods that help interact with it. Then when it is inherited by another class, say in this case a car; a more specific type of vehicle we can add attributes and methods that are unique to that car and using inheritance also add the previously defined ones aswell. This is done through what is called the super() function, this tells the object to inherit everything from its base class on initialisation. 

**💡 R** : As a result the programs and code I wrote become a lot more reusable, making more sense to our philosiphy of DRY; standing for do not repeat yourself, through another OOP concept called polymorphism we are able to make our code more flexible, through encapsulation we are able to make our code more restricted and secure and finally through abstraction we can hide the level of complexity behind classes; so the user only sees what they need to see. This style of programing is not better that functional programming, but a preference and it is what I have used since the first year of university and see as an amazing concept to help write effective, clean and reusable code.

# Question 9

* **A** : Why do we use TDD?

**📋 S** : Test Driven Development is the practice of writing a test for a piece of required functionality, before writing any implementaiton code. It is commonly known as a discipline among programmers as it requires you to be studious in the way you go about it; so once you have written a test you should refrain from writing more tests or altering the current one until you have successfully got it to pass. These tests are usually written by subject-matter experts and assume the way we want the program to behave in terms of output.

**📌 T** : During the python programming week I was given the task of creating a calculator; nothing special just a calculator capable of performing the basic arithmetic functions such as (+, -, /, x). 

**👔 A** : This was a perfect opportunity to write some tests and then test them against my calculator before I was going to create. The whole concept of TDD is to create the test before you begin to implement, so I made a test using the unittest module in python and it took a method I had created inside an empty calculator class and took the same arguments that method would have taken and had a expected output. The first should always fail; as this one did. I then implemented the addition function in my calculator and ran the test again; this time it had passed meaning I had adhered to a TDD approach of developing this calculator.

**💡 R** : TDD is a very important and vital practice not only in programming but also in DevOps as these are the tests that can be automated every time you send your code to integrate; depending on the outcome the code will either be rejected or accepted. This allows for less bugs in the final product, development towards acceptance criteria in the tests and overall tidier more precise code written by the developer. It is also quite easy to create these test as they aren't dependent on what is needed behind the scenes like some modules in python for example and they also allow for safer refactoring of code if you need to make changes in the future.