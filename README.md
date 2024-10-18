# Learning CI/CD
- [Learning CI/CD](#learning-cicd)
  - [What is CI? Benefits?](#what-is-ci-benefits)
  - [What is CD? Benefits?](#what-is-cd-benefits)
  - [Difference between CD and CDE](#difference-between-cd-and-cde)
  - [What is Jenkins?](#what-is-jenkins)
    - [Why Use Jenkins?](#why-use-jenkins)
    - [Benefits of Jenkins](#benefits-of-jenkins)
    - [Disadvantages of Jenkins](#disadvantages-of-jenkins)
    - [Stages of Jenkins](#stages-of-jenkins)
    - [What alternatives are there for Jenkins](#what-alternatives-are-there-for-jenkins)
  - [Why build a pipeline? Business value?](#why-build-a-pipeline-business-value)
  - [Diagram of CI/CD](#diagram-of-cicd)
- [CI / CD pipeline](#ci--cd-pipeline)
  - [Why build a CI/CD pipeline?](#why-build-a-cicd-pipeline)
  - [Why Jenkins?](#why-jenkins)
  - [Buniness value?](#buniness-value)
- [Jenkins](#jenkins)
  - [Log in into Jenkins](#log-in-into-jenkins)
  - [Create a new job(or + New Item)](#create-a-new-jobor--new-item)
  - [Configure:](#configure)

## What is CI? Benefits?
 
**CI (Continuous Integration)**: A development practice where developers integrate code into a shared repository frequently.
 
**Benefits**: Early bug detection, reduced integration issues, improved collaboration, and faster feedback loops.
 
## What is CD? Benefits?
 
**CD (Continuous Deployment/Delivery)**: Automates deployment processes to ensure that code changes are automatically prepared or deployed to production.
 
**Benefits**: Accelerated release cycles, reduced manual intervention, consistent deployment processes, and faster time-to-market.
 
## Difference between CD and CDE
 
**CD (Continuous Delivery)**: Prepares code for release but may require manual approval for deployment.
 
**CDE (Continuous Deployment)**: Automates deployment to production without manual steps.
 
## What is Jenkins?
 
**Jenkins**: An open-source automation tool for CI/CD pipelines, supporting plugins to build, test, and deploy applications.
 
### Why Use Jenkins?
 
* **Automation of CI/CD**: Jenkins automates repetitive tasks in the CI/CD process, reducing the chance of human error and speeding up software delivery.
* **Open-source with Community Support**: Jenkins is free to use and has a large, active community, making it easier to find resources, tutorials, and plugins.
* **Flexible and Extensible**: With hundreds of plugins, Jenkins can be customized to fit a wide range of project needs and integrate with various tools, such as Git, Maven, Docker, and Kubernetes.
* **Scalability**: Jenkins can scale to accommodate large, complex projects by distributing workloads across multiple nodes.
 
 
### Benefits of Jenkins
 
* **Automation**: Saves time by automating the entire CI/CD pipeline, from code commit to deployment.
* **Flexibility through Plugin**s: Jenkins has over 1,800 plugins, allowing integration with almost any tool in the development and deployment process.
* **Scalability**: Supports distributed builds across multiple machines, ideal for large projects.
* **Continuous Monitoring**: Allows for constant feedback on code quality and deployment status, enabling faster and more reliable releases.
 
### Disadvantages of Jenkins
 
* **Complexity**: Setting up and managing Jenkins can be complex, especially for teams new to CI/CD.
 
* **Plugin Management Overhead**: With many plugins available, ensuring compatibility and managing plugin updates can be time-consuming.
 
* **Resource-Intensive**: Jenkins can be resource-heavy, especially when running large numbers of builds or supporting complex pipelines.
 
### Stages of Jenkins
 
**Stages**: Code, Build, Test, Deploy.
 
### What alternatives are there for Jenkins
 
**Alternatives**: GitLab CI/CD, CircleCI, Travis CI, GitHub Actions, Bamboo.
 
## Why build a pipeline? Business value?
 
**Pipeline Benefits**: Streamlines development, ensures quality, reduces errors, enables faster and reliable software delivery, and aligns with agile business needs.
 
## Diagram of CI/CD
 
**Diagram Elements**: Code → Build → Test → Release → Deploy → Monitor.
 
*Understand SDLC workflow: plan, design, develop, deploy*
 
**SDLC Workflow**: Sequential phases where requirements are planned, solutions designed, software developed, and then deployed to production, ensuring systematic development.



# CI / CD pipeline

![CI-CD](./cd-ci.jpg)


## Why build a CI/CD pipeline?
- run one command to do it all
- done in minutes

## Why Jenkins?
- industry standard (been in indrustry for a while)
- free to use
- open source
- powerful and many plugins 
- help us to understand the CI/CD pipeline

## Buniness value?
- save time -> save money





# Jenkins 


## Log in into Jenkins
 
1. Having a server already set up with the **user name** and **passord** 
2. Log in with the username and passord

![jenkins](images/jenkins.jpg)

## Create a new job(or + New Item)

1. Click on the **Create a new job** 
   
![project](images/project.jpg)

2. **Enter a item name** : `maria-first-project`
   
3.  Select **Freestyle project** then click **OK**
  
## Configure:

![configure](images/configure.jpg)
 
1. **Description** : testing jenkins
2. **Enable Discard old builds**
3. **Max # of builds to keep** : `5` 
   
4. **Build Steps**
   - click build steps
  
    ![build stage](<images/build steps.jpg>)
  
     - select execute shell

    ![execute shell](<images/execute shell.jpg>)