# Learning DevOps for Non-Engineers
A Guide for Non-Technical Users

Basic skills to land your first job as a DevOps

## Index
1. [Roadmap](#roadmap)
1. [Introductory Questions](#introductory-questions)
1. [Courses](#courses)
1. [Job Offers](#job-offers)

## Roadmap
1. Learn a Programming Language for Automation
    - Python
    - Go
1. Learn Git (clone,branch,add,commit,pull,push,checkout)
1. Learn Linux
    1. Learn to live in Terminal
        - Bash scripting
        - Powershell scripting
        - Vim/Nano/Emacs (Some text editors)
        - Text Manipulation Tools (awk, sed, grep, cat, echo, tr, cut, etc)
        - Process Monitoring (ps, top, etc)
        - Network Tools (ping, netstat, tcpdump, firewalld, iptables, etc)
1. Containers
    - Docker
1. Container Orchestration
    - Kubernetes
1. Learn CI/CD Tools
    - Jenkins
    - GitLab CI
    - Azure Pipelines
    
    >Once you reach point 6 (Learn CI/CD Tools), you will be ready to start your job/internship search. By focusing on the skills that are in demand in the market and highlighting your technical abilities, you will be well-positioned to compete for a range of job opportunities.

1. Infrastructure as a Code
    1. GitOps
        - ArgoCD
    1. Service Mesh
        - Istio
        - Linkerd
    1. Infrastructure Provisioning
        - Terraform
    1. Configuration Management
        - Ansible
1. Observability. Learn how to monitor software and infrastructure
    1. Logs Management
        - Elastic Stack (Elasticsearch, Logstash, Kibana)
    1. Infrastructure Monitoring
        - Prometheus
        - Grafana



## Introductory Questions
1. What is Git?
    
    Git is a distributed version control system that allows developers to track changes to source code files and collaborate on software development projects. It was created by Linus Torvalds in 2005 to manage the development of the Linux kernel.

1. What is Linux and why should I learn Linux commands?
    
    Linux is an open-source operating system that is widely used on servers and in the development of software applications. It was first introduced in 1991 by Linus Torvalds, and since then it has become a popular choice for both developers and system administrators.

    Knowing Linux commands is essential for working as a DevOps because many of the tools and technologies used in DevOps are based on Linux

1. What is DevOps Culture?

    DevOps culture is a set of values, principles, and practices that aim to bring software development and operations teams together to deliver high-quality software faster and more efficiently. At its core, DevOps culture emphasizes collaboration, communication, and automation to achieve these goals.

1. What is a Container and why is it useful in software development?

    A container is a software package that bundles an application and all of its dependencies together in a self-contained, isolated environment. The containerization technology allows for software to run reliably and consistently across different computing environments, from development to production, without being affected by the differences in the underlying infrastructure.

1. Microservice vs Monolith

    Microservices and monolithic architectures are two different approaches to software development, with different advantages and disadvantages.

    A monolithic architecture is a traditional approach to software development, where all components of an application are developed and deployed as a single, tightly-coupled unit. This means that any changes to one part of the application can affect other parts of the application, making it difficult to modify and scale.

    In contrast, a microservices architecture is an approach where an application is composed of small, independently deployable services that communicate with each other via APIs. Each microservice performs a specific task or function, and can be developed and deployed independently of the other microservices in the system. This enables faster development, more efficient resource utilization, and easier scaling of the application.

1. What is Kubernetes?

    Kubernetes (also known as "K8s") is an open-source container orchestration platform originally developed by Google. It is one of the most popular container orchestration platforms available today, and is used by organizations of all sizes to manage and deploy containerized applications.

    A container orchestrator is a tool or platform used to manage and deploy containers at scale. Container orchestrators automate the deployment, scaling, and management of containerized applications across a cluster of hosts.

1. What is CI/CD?

    CI/CD stands for Continuous Integration/Continuous Delivery. It is a software development practice that aims to automate the process of integration, testing, and delivery of new features to end-users in a continuous and frequent manner.

    Continuous Integration (CI) refers to the practice of integrating code changes into the repository frequently and automatically to detect errors and conflicts as early as possible. This involves running automated tests on each code change to ensure that the code still functions correctly.

    Continuous Delivery (CD) refers to the practice of delivering developed features frequently and automatically through an automated deployment process. This involves executing additional tests to ensure that the software meets quality, security, and functionality requirements.

    The goal of CI/CD is to accelerate the software delivery process, reduce the risk of errors and conflicts in production, and enable developers to focus on developing new features rather than spending time on manual testing and deployment tasks.

1. What is Observability?

    Observability refers to the ability to gain insight into the internal workings of a system or application through the collection, analysis, and visualization of relevant data. It involves monitoring and logging all aspects of the system, including infrastructure, application code, and user interactions, to gain a complete understanding of its behavior.

    Observability allows DevOps teams to detect and diagnose issues quickly and efficiently, reducing downtime and improving system reliability. It involves collecting metrics, logs, traces, and other data from various sources and correlating them to identify the root cause of any problems.

    In summary, observability is a critical component of modern DevOps practices that enable teams to monitor and analyze system behavior, improve performance, and provide a better experience for users.

1. How to land my first job in DevOps with no experience in IT?

    Landing your first job in DevOps with zero experience in IT can be challenging, but it is not impossible. Here are some tips that may help:

    - Research: Start by researching and learning about DevOps. Read articles, books, and take some online courses. This will help you understand the concepts and tools used in DevOps.

    - Do personal projects: Carry out some personal DevOps projects. If you have no previous experience in IT, you can start with simple projects to learn the tools and processes.

    - Create a portfolio: Create an online portfolio that showcases your personal projects and your DevOps skills. This can be helpful to present yourself to potential employers.

    - Connect with other DevOps professionals: Join online DevOps groups and communities, attend events and conferences related to DevOps. This will help you meet other industry professionals and learn from them.

    - Look for DevOps-related jobs: Look for DevOps-related jobs, even if they are entry-level positions. Many companies are willing to train people with little experience if they show passion and skills in the subject.

    - Show your attitude: When you go to job interviews, show your attitude and passion for DevOps. Be honest about your level of experience, but emphasize your willingness to learn and work hard.

    Remember that the path to landing your first job in DevOps can take time and effort, but with perseverance and dedication, you can achieve it.

    >Having a DevOps mentor can be very helpful when it comes to landing your first job in DevOps. A mentor who has experience working in the field can provide you with valuable insights and advice on what it takes to succeed as a DevOps professional.
    >
    >They can share their experiences and give you an idea of what to expect in terms of the skills and knowledge required to work in DevOps. They can also help you identify the areas where you need to improve your skills and knowledge, and provide you with resources and learning materials to help you develop those skills.
    >
    >In addition, a DevOps experienced mentor can help you make connections in the industry, which can be invaluable when it comes to finding job opportunities. They may know of job openings or be able to introduce you to people who can help you find a job.
    >
    >Overall, having a DevOps experienced mentor can be a great asset when it comes to landing your first job in DevOps. However, it's important to remember that ultimately, your success will depend on your own efforts and dedication to learning and developing your skills.


## Courses

The following courses are sorted per priority. You must start with the first one from the top to the bottom.

### Free courses

These are some free courses from edX.

edX offers courses from a variety of entities including top-ranked universities, nonprofit organizations, and corporations. Some of the entities that offer courses on edX include:

- Google
- Microsoft
- IBM
- Red Hat
- Linux Foundation
- Amazon Web Services
- ETH Zurich
- Harvard University
- Massachusetts Institute of Technology (MIT)
- University of California, Berkeley

1. [Introduction to DevOps and Site Reliability Engineering](https://www.edx.org/es/course/introduction-to-devops-and-site-reliability-engineering?index=spanish_product&queryID=106ad6c63e2aaefc3f54261871bd8bc6&position=2)

1. [Git for Distributed Software Development](https://www.edx.org/es/course/git-for-distributed-development?index=spanish_product&queryID=c1f1b948aef5009821bf890a8d731b22&position=2)

1. [Linux Commands & Shell Scripting](https://www.edx.org/es/course/linux-commands-shell-scripting)

1. [DevOps on AWS: Code, Build, and Test](https://www.edx.org/es/course/devops-aws-code-build-test)

1. [Introduction to Containers, Kubernetes and OpenShift](https://www.edx.org/es/course/introduction-to-containers-kubernetes-and-openshift?index=spanish_product&queryID=11b3bfb1904fa86ef84dc52374784b28&position=2)

1. [Introduction to Kubernetes](https://www.edx.org/es/course/introduction-to-kubernetes)

1. [Scripting with Python](https://www.edx.org/es/course/scripting-with-python)

### Paid courses

A Cloud Guru [acloudguru.com](acloudguru.com)

## Job Offers

In the following section, we will provide an overview of job opportunities in the current market. We will outline the specific skills that are in high demand, along with the tasks that you can expect to perform in these roles. Additionally, we will include salary information to give you an idea of the earning potential for each position. Whether you're just starting your career or looking for a new challenge, these job opportunities offer a range of options for those with the right skills and experience. Read on to learn more about the exciting possibilities that await you in today's job market.

>It is important to focus on the technical skills that are in demand in the job market rather than getting caught up in specific experience requirements. Many companies are willing to hire candidates with little to no experience as interns or entry-level employees, as long as they possess the necessary technical skills.

Some job oportunities are:

![](/images/offer%20(9).png)

![](/images/offer%20(8).png)

![](/images/offer%20(7).png)

![](/images/offer%20(2).png)

![](/images/offer%20(10).png)

![](/images/offer%20(12).png)

![](/images/offer%20(11).png)

![](/images/offer%20(6).png)

![](/images/offer%20(4).png)

![](/images/offer%20(5).png)

![](/images/offer%20(1).png)

![](/images/offer%20(3).png)
