# Jenkins Job 

### As we are going to build Java Based Application which required maven build tool to be installed on master node: 

### 0. Install Maven 
```
apt-get install maven -y 
```

### 1. Login Jenkins 

### 2. Click on New Item from the Left Menu 

### 3. Now Provide the below Details: 
```
Name: EasyBuggy
SCM : Select -> Git 
Type: FreeStyle Job 
Repo: https://github.com/amitvashisttech/applicationtesting-sast-dast-aristocart-04-Jun-2024.git 
Branch : */main 
Go to Build Steps -> Select Execute Shell -> Supply the Linux Command of your choice. 
```

```
cd 03-Easybuggy
mvn clean 
mvn compile 
mvn package 
```

### 4. Now Run / Build Now the Job 

### 5. Check the Job Status & Check the build ID for more details. 

### 6. Click on Console Outputs to see what command is executed.

### 7. We would like to capture artifacts for EasyBuggy. 

### 8. Edit the existing Job -> Go to Post Build Action -> Archive Artificates
```
03-Easybuggy/target/*.jar
```  
### 9. Now Run / Build Now the Job & this time you should able to see the artifact on jenkins job web page itself & you can also download the same.  
