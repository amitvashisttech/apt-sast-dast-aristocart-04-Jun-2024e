# Install SonarQube for SAST 

## Step 1: Login to master nodes

## Step 2: Run the following command for Virtual Memory Max Count:
```
sysctl -w vm.max_map_count=262144
```

## Step 3: Git pull 

## Step 4: Go to SonarQube Directory

## Step 5: Run Docker Common
```
docker-compose up -d 
```


## Step 6: Check sonarqube is running or not & also check the port no. 
```
docker ps 
```

## Step 7: Login to SonarQube Webpage [http://masterip:9000 ] & Credentials : admin/admin 

## Step 8: We need to genrate a tocker sonar & jenkins integration. 
```
- Click on Adminstrator Tab
- Click on Security Sub Menu 
- Select the Users 
- Click on the Token Menu 
- Create a new token & make a note of that. 
```

## Step 9: Now we need to downlaod SonarQube integation plugin 
```
https://updates.jenkins.io/download/plugins/sonar/

Version : 2.8.1 
```

## Step 10: Upload the download Plugin & Install 
```
1. Click -> Manage Jenkins -> Plugin -> Advance Setting Tab -> Choose -> brower the plugin from your local machine -> Deploy.
```

## Step 10: Install the same in jenkins by uploading it & restart Jenkins.
```
systemctl restart jenkins 
```


## Step 11: We need to configure SonarQube Settings in Jenkins. 
```
1. Click -> Manage Jenkins -> Configure System -> System -> Search for SonarQube Server Section & Provide the required detials:

Name: Sonar
Server URL : http://172.31.0.100:9000
Server Auth Token : <what-we-have-genrated-from-sonarqube>
```

  
