This is my fixed for dadlasd Deloitte
For any questions - Please email me at DevOps@RajeshKumar.xyz
# ========================NEXUS==============================

<distributionManagement>
	<repository>
		<id>tata</id>
		<name>Internal Releases</name>
		<url>http://35.180.189.66:8081/repository/scmgalaxy/</url>
	</repository>
 
	<snapshotRepository>
		<id>tata</id>
		<name>Internal Releases</name>
		<url>http://35.180.189.66:8081/nexus/content/repositories/snapshot/</url>
	</snapshotRepository>

</distributionManagement>


===============ARTIFACTORY=================
<distributionManagement>
	<repository>
		<id>depoyment</id>
		<name>Internal Releases</name>
		<url>http://35.180.189.66:8081/artifactory/list/rajesh-release/</url>
	</repository>
 
	<snapshotRepository>
		<id>farhan</id>
		<name>Internal Releases</name>
		<url>http://35.180.189.66:8081/artifactory/list/rajesh-snapshot/</url>
	</snapshotRepository>

</distributionManagement>

=====================SETTING.XML=================================
   <server>
		<id>farhan</id>
		<username>farhan-user</username>
		<password>123456</password>
</server>

=======================Setting.xml with Artifactory Setup======================
<mirror>
      <id>central</id>
      <name>Maven Repository Manager running on repo.mycompany.com</name>
      <url>http://35.180.189.66:8081/artifactory/list/group/</url>
      <mirrorOf>*</mirrorOf>
    </mirror>
    
    

