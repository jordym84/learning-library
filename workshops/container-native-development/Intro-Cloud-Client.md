# Workshop Introduction

## Container Native Application Development Workshop Overview

Welcome to the Oracle Public Cloud Container Native Development workshop. This workshop will walk you through the process of moving an existing application into a containerized CI/CD pipeline and deploying it to a managed Kubernetes service in the Oracle Public Cloud.

You will take on 2 personas during the workshop. The Lead Developer Persona will be responsible for configuring the parts of the automated build and deploy process that involve details about the application itself. The DevOps Engineer Persona will configure the parts of the automation involving the Kubernetes infrastructure. To containerize and automate the building and deploying of this application you will make use of Wercker Pipelines, Oracle Container Registry, and Oracle Container Engine.

# Workshop Prerequisites

### **Step 1**: Acquire an Oracle Cloud Trial Account

- If you do not have a trial account please click on this URL [cloud.oracle.com/tryit](http://cloud.oracle.com/tryit&intcmp=DeveloperInnovation-HOL-11NOV17), and complete all the required steps to get your free Oracle Cloud Trial Account.

- You will eventually receive the following email. You may begin working on Lab 100 before you receive this email, but you will not be able to start Lab 200 until you have received it.
![](images/oraclecode/code_9.png)
_Please note that this email may arrive in your spam or promotions folder pending your email settings._

- Once you receive it, click the **Get Started with Oracle Cloud** button to sign in using the temporary password found in the email. You will be prompted to change your password. During this process, please also provide answers to the **security questions** so that you will be able to reset your password if you cannot remember it.

### **Step 2**: Connect to Your Cloud-Hosted Client VM

To provide the best possible experience during your time at Oracle Code your instructor has created a client VM prior to your arrival. The environment contains all the tools required to perform today's labs. To access the environments please follow the steps below.

- Download [VNC Viewer](https://www.realvnc.com/en/connect/download/viewer/).  

![](images/oraclecode/code_1.png)

- Double Click on the downloaded file to open VNC Viewer.

![](images/oraclecode/code_2.png)

- Your Instructor will you with access to a Linux image with all the required development software to complete today's Lab. Please look at the handout provided by your instructor and take note of the VNC host and password fields.

![](images/oraclecode/code_3.png)

- Enter your VNC Host IP address into the VNC Viewer and press enter.

![](images/oraclecode/code_4.png)

- Enter your VNC Host password into the VNC Viewer prompt and press enter.

![](images/oraclecode/code_5.png)

- You receive the unecrypted connection message below, please check the box and press continue.

![](images/oraclecode/code_8.png)

- You can now begin Lab 100. Please click on the Hamburger icon at the top of the page, then select Lab 100.

![](images/oraclecode/code_6.png)

![](images/oraclecode/code_7.png)