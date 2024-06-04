# In the following demo will be setting up 3 Node ( 1 Master & 2 Worker Nodes ) 

 

## Now provision three virtual machines with following commands:

### Step 1: Open Windows Powershell / Cmder
### Step 2: Navigate to Vagrant Setup Directory 
```
cd vagrant-setup/devops
```

### Step 3: Checking the status of existing virtual machines  
```
vagrant status 
```

### Step 4: Bring up all the virtual machines mentioned in Vagrantfile 
```
vagrant up master
```
### In Case you want to bring up all the virtual machines
```
vagrant up
```

### Step 5: Login inside the virtual machine via ssh 
```
vagrant ssh master 
```
### Step 6: Become a super user 
```
sudo su - 
```

### Step 7: Clone our project repo
```
git clone https://github.com/amitvashisttech/applicationtesting-sast-dast-aristocrat-04-Jun-2024.git
```


