# activiti-springboot
it's a puttering around for activiti workflow integrated with spring boot

ACTIVITY7
按官方文档：
加<activiti-dependencies.version>7.1.123</activiti-dependencies.version>
<dependencyManagement>
    <dependencies>
      <dependency>
        <groupId>org.activiti.dependencies</groupId>
        <artifactId>activiti-dependencies</artifactId>
        <version>${activiti-dependencies.version}</version>
        <scope>import</scope>
        <type>pom</type>
      </dependency>
    </dependencies>
  </dependencyManagement>

		<dependency>
    		<groupId>org.activiti</groupId>
    		<artifactId>activiti-spring-boot-starter</artifactId>
		</dependency>


报错，下不到文件，加自定义repo
	<repositories>
	    <repository>
	      <id>alfresco</id>
	      <name>Activiti Releases</name>
	      <url>https://artifacts.alfresco.com/nexus/content/repositories/activiti-releases/</url>
	      <releases>
	        <enabled>true</enabled>
	      </releases>
	    </repository>
	</repositories>
