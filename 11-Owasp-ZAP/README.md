# Install OWASP ZAP on Windows 

### Step 1: Download Java Runtime or Dev Kit on windows & version should be higher then 11. 

### Step 2: Download Owasp Zap for Windows & Run the installer 

### Step 3: Download Owasp Juice App & run inside master node as container.

```
docker run -d --name juice -p 8002:3000 amitvashist7/owasp-juice-shop
```

### Step 4: Go to Zap App & Start the Automated Attack on Juice WebSite : http://172.31.0.100:8002

### Step 5: Post Complation of Attack, check the Alert Menu for more details on Bugs

### Step 6: Genrate the report by click on the Report form the Top Menu & Select the Juice App URL & Finish. 

### Step 7: Now you can review the Report in details & click on the CVE icons for more details on it. 
