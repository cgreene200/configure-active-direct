# Active Directory Project:

In this tutorial we will practice performing activities on a network in an Azure virtual environment.

We will see the actual raw traffic being transmitted between the 2 virtual machines. I hope this gives a better understanding of firewalls.

## What Azure resources will we be working with?
* Azure Virtual Machines (Windows 10 and Microsoft Server 2022)
* Azure Network Security Groups (Firewall Resources)

## What Software Tools will we be working with?
* Many command line tools
* Powershell
* Remote Desktop

## Operating Systems Used
•	Windows 10
•	Microsoft Server 2022

## What the following screenshots will show?
## Setup Active Directory
1.	How to install Active Directory Domain Services
2.	How to promote server to a domain controller
3.	How to Create an Organizational Unit
4.	How to Create a new user
5.	How to Turn a "New User" into an "Administrative User"
6.	How to Join a user to the domain
7.	How to reset network passwords

## 1.  Steps to Install Active Directory Domain Services
### To start installing Active Directory, click on "Start" and click on "Server Manager" in order to get to the following page:

![alt text](https://i.imgur.com/ZGUJ54J.png)

## Click on (Add Roles and Features), to start the installation process, as shown above.

![alt text](https://i.imgur.com/qCQmCfW.png)

## Click on "Next", as shown above.

![alt text](https://i.imgur.com/ykQgBy1.png)

## Accept the default and then click "Next", as shown above.


![alt text](https://i.imgur.com/62Uzi9W.png)

## We're installing it on the selected computer, as shown above.

![alt text](https://i.imgur.com/zbOVgwO.png)

## Make sure you choose "Active Directory Domain Services" and then hit "Next", as shown above.

![alt text](https://i.imgur.com/7KLR70E.png)

## Accept the default and then click "Next", as shown above.

![alt text](https://i.imgur.com/xe6Wezw.png)

## Click on "Next", as shown above.

![alt text](https://i.imgur.com/1lBpud5.png)

## Click on "Install", to start the installation process.


![alt text](https://i.imgur.com/j9mh3uP.png)

## Intalling.............

![alt text](https://i.imgur.com/u71Bpp0.png)

## Installing.............

![alt text](https://i.imgur.com/AW0QS4c.png)

## Installed......Click on "Close"

## This installation is finished!


## 2.  Steps to "Promote Server to Domain Controller"
### After "Active Directory completes the installation, focus on the "upper right corner" of screen, as shown below:

![alt text](https://i.imgur.com/TTNUHK5.png)

## Click on **"Promote this server to a domain controller"**, as shown circled above.

![alt text](https://i.imgur.com/QIkiHkC.png)

## This turns the Active Directory server into a domain controller.

![alt text](https://i.imgur.com/oLmVe6W.png)

## Here, we're going to "add" a new forest and give the new domain a name, as shown above.

![alt text](https://i.imgur.com/hp3akMP.png)

## Create a domain password.

![alt text](https://i.imgur.com/RZjPvIu.png)

## Click "Next".

![alt text](https://i.imgur.com/lhBeY7C.png)

## Click "Next".

![alt text](https://i.imgur.com/Zedfkn8.png)

## Click "Next".

![alt text](https://i.imgur.com/3fYyfqB.png)

## Click "Next".

![alt text](https://i.imgur.com/Sg5M7bj.png)

## Click on "Install", as shown above

![alt text](https://i.imgur.com/DoQYtSL.png)

## Installing...........

![alt text](https://i.imgur.com/eF61JeB.png)

## Restarting...........

## This installation is finished...........

## 3.  How to create an "Organizational Unit"
## The following shows how to access "Active Directory Users and Computers", as shown below:
## To create an "Organizational Unit" 

![alt text](https://i.imgur.com/oorwsET.png)

## Click on "Active Directory Users and Computers" and see "Tester'sDomain.com", as shown below.

![alt text](https://i.imgur.com/vIgbbdg.png)

## Right-click on "Tester'sDomain.com" and go down to "New" and over to "Organizational Unit", as shown below.

![alt text](https://i.imgur.com/lE5Gtsh.png)

## Create a new "Organizational Unit" called, "_ADMINS" and click "OK", as shown below.

![alt text](https://i.imgur.com/ddqkWJw.png)

## To create a "new" user withing the "_ADMINS" folder, start by "selecting" the "ADMINS" folder, as shown below.

![alt text](https://i.imgur.com/UYvlfFy.png)

## Finished!!

## 4.  How to create a "New User"

## Create the "New User" by "right-clicking" on "_ADMINS" and go down to "New" and over to "User", as shown below.

![alt text](https://i.imgur.com/R6T7ahm.png)

## Click on "User" to start filling in the user information and then click on "Next", as shown below.

![alt text](https://i.imgur.com/EkZE5F5.png)

## Next, create a password and then click "Next", as shown below.

![alt text](https://i.imgur.com/xK9ZLba.png)

## Now, click "Finish" to complete the task.

![alt text](https://i.imgur.com/W5jg4wD.png)

## Now, here's the "new user" finally completed, as shown below.

![alt text](https://i.imgur.com/15ly75T.png)

## Finished!..........

## 5.	How to Turn a "User" into an "Administrative User"

