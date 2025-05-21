# Create Fargate Profile for EKS Cluster

## **Project Overview**
This project demonstrates the use of AWS fargate to deploy containers and pod into our cluster. Amazon Fargate is a serverless compute engine for containers provided by AWS. It allows you to run containers without having to manage the underlying infrastructure (i.e., you don’t need to provision or manage EC2 instances). .Limitation: No support for stateful application and Daemon Sets yet and 1 pod per virtual machine.

---
  
## **Feature**

### **Creates Fargate role**
 - Create a role for EKS service to use Fargate.
 - Name the role and create the role.
 - Select Fargate pod role.
 - Now create a Fargate profile.
 - Create a namespace selected in the Fargate profile on the terminal.


## **Diagrammatic Presentation**
 - Create a role for EKS service to use Fargate.
 - Name the role and create the role.
    ![image](https://github.com/user-attachments/assets/e4e58cf2-b8f7-46b1-b750-d6d8abd7e397)
 - Select Fargate pod role.
 - Now create a Fargate profile.
   ![image](https://github.com/user-attachments/assets/40009f9a-36ab-4248-8d4c-1d5f393120b6)


 - Conncet to the EKS cluster
 - Create a namespace selected in the Fargate profile on the terminal.
   
   ![image](https://github.com/user-attachments/assets/2bf64ec1-844f-41a2-af18-f83ea99835ac)


   ![image](https://github.com/user-attachments/assets/efcb1260-c01d-4a18-94af-9fbba350f779)



 








	
