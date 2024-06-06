## SCA Demo: 

1. Login to Snyk Website -> SignUP
2. Add Project -> GitHub -> Provide Repo. -> EasyBuggy App. -> Add Select Repo.
3. It will Identify the 3rd Party Lib, if its a Java Based App then will find 3rd Party Dependency in pom.xml.
4. Clink on pom.xml 
5. Now you can check CVS - Common Vunrability Score out of 10. 
6. It will display which 3rd party lib & version causing this issue & also suggest the fixed Version as well. 

7. Let's expand pom.xml -> It will identified all the third part lib. -> Select pom.xml -> Check "commons-fileupload:commons-fileupload" -> Show more details ->
 - Check introduce thoough 
 - Fix 

8. Now check the -> mysql:mysql-connector-java 
 - Introduced through : mysql:mysql-connector-java@5.1.25
 - Fixed in :  mysql:mysql-connector-java@5.1.35



Look for commons-fileupload:commons-fileupload

** CVSS : Common Vunrability Score System 
** CVE : Common Vunrability Exposure
** CWE : Common Weakness Enumeration
