# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

```
NAME : SANKAR S
REG NO: 212224040291
DEPT : CSE

```
# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![1](https://github.com/user-attachments/assets/97ef3725-8a8f-4cdc-86e1-70088dd85345)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:


![1](https://github.com/user-attachments/assets/09142f7b-cd8f-4123-89d3-58e542ba84bd)




It displays the following menu and select 2 for Website Attack Vectors:

![2](https://github.com/user-attachments/assets/92370624-dba8-4355-bd07-5de04db60e59)



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![3](https://github.com/user-attachments/assets/21affeb1-00a0-4f2b-995e-fbcc3b48bbad)



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:




![4](https://github.com/user-attachments/assets/ce7ce0d3-bd6c-42bc-bc32-8678de599060)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![5](https://github.com/user-attachments/assets/216cd6c1-3eb0-4c49-9602-7e6589d067d0)



It shows the following screen in which the option Google can be selected:



![6](https://github.com/user-attachments/assets/382474cc-8dc3-42bb-b484-3bf19c08ad6f)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![7](https://github.com/user-attachments/assets/36bd2b89-09fc-4660-8ae5-3cfaedd7aec1)



In windows IE, on giving the url http://192.168.95.177, the fake Google page is displayed. The victim can enter the username and password
![8](https://github.com/user-attachments/assets/1db45a3c-5b6b-4b96-a8b1-264cc28fb270)



SET logs the information regarding the Google credentials:

![9-2 (1)](https://github.com/user-attachments/assets/77ae64c3-f545-4954-8c90-0fcfdc0ce944)


SET logs the information in the xml file under /root/.set directory:

![10](https://github.com/user-attachments/assets/e00c7066-9c2a-421d-b214-719fe2ce9df7)





## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
