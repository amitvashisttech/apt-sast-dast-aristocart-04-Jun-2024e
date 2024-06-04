# Jenkins Setup

### Note : I've already install jenkins at the first place. 

### Step 1: Check installed Jenkins status 
```
systemctl start jenkins; systemctl status jenkins 
```

### Step 2: Check Jenkins Network Port
```
netstat -tulnp 
```

### Step 3: Now we need to login to Jenkins Web Console
```
ip addr 
```

### Step 4: Now Open Jenkins URL in web browers of your choice

### Step 5: Jenkins probably ask you initial credentials. 
```
cat /var/lib/jenkins/secrets/initialcredentials
```

### Step 6: Step your login name. 
