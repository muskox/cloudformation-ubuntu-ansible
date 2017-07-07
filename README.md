# Cloudformation Ubuntu with Ansible

## Installation

### Step 1

Login to your AWS console and search for Cloudformation.

![](https://raw.githubusercontent.com/muskox/cloudformation-ubuntu-ansible/master/images/Cloudformation1.png)

### Step 2

Create a new stack with this template.

![](https://raw.githubusercontent.com/muskox/cloudformation-ubuntu-ansible/master/images/Cloudformation2.png)

### Step 3

Choose the template from this repo and upload it.

![](https://raw.githubusercontent.com/muskox/cloudformation-ubuntu-ansible/master/images/Cloudformation3.png)

### Step 4

Give the cloudformation stack a Name and use one of your keys already on the system. The KeyName parameter should have a drop down with your ssh keys. 

![](https://raw.githubusercontent.com/muskox/cloudformation-ubuntu-ansible/master/images/Cloudformation4.png)

### Step 5

Add optional Tags if you so desire. Click Next.

![](https://raw.githubusercontent.com/muskox/cloudformation-ubuntu-ansible/master/images/Cloudformation5.png)

### Step 6

Click Create.

![](https://raw.githubusercontent.com/muskox/cloudformation-ubuntu-ansible/master/images/Cloudformation6.png)

### Step 7

Watch Cloudformation do its thing. Watch for errors in this step.

![](https://raw.githubusercontent.com/muskox/cloudformation-ubuntu-ansible/master/images/Cloudformation7.png)

### Step 8

A successful cloudformation stack creation looks like this.

![](https://raw.githubusercontent.com/muskox/cloudformation-ubuntu-ansible/master/images/Cloudformation8.png)

### Step 9

Now go to EC2 and see your node. Be patient as it may still be running its Status Checks.

![](https://raw.githubusercontent.com/muskox/cloudformation-ubuntu-ansible/master/images/Cloudformation9.png)


