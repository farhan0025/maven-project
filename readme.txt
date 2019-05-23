This is my fixed for dadlasd Deloitte
For any questions - Please email me at DevOps@RajeshKumar.xyz
# ========================NEXUS==============================

<distributionManagement>
	<repository>
		<id>tata</id>
		<name>Internal Releases</name>
		<url>http://52.47.164.4:8081/repository/scmgalaxy/</url>
	</repository>
 
	<snapshotRepository>
		<id>tata</id>
		<name>Internal Releases</name>
		<url>http://52.66.106.91:8081/nexus/content/repositories/snapshot/</url>
	</snapshotRepository>

</distributionManagement>


===============ARTIFACTORY=================
<distributionManagement>
	<repository>
		<id>rajesh</id>
		<name>Internal Releases</name>
		<url>http://52.47.164.4:8081/artifactory/list/rajesh-release/</url>
	</repository>
 
	<snapshotRepository>
		<id>rajesh</id>
		<name>Internal Releases</name>
		<url>http://52.47.164.4:8081/artifactory/list/rajesh-snapshot/</url>
	</snapshotRepository>

</distributionManagement>

=====================SETTING.XML=================================
   <server>
		<id>rajesh</id>
		<username>farhan-user</username>
		<password>123456</password>
</server>

=======================Setting.xml with Artifactory Setup======================
<mirror>
      <id>central</id>
      <name>Maven Repository Manager running on repo.mycompany.com</name>
      <url>http://52.47.164.4:8081/artifactory/list/group/</url>
      <mirrorOf>*</mirrorOf>
    </mirror>
    
    

