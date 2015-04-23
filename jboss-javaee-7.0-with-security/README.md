WildFly JBoss Java EE 7 with Security
=============================

This BOM builds on the Java EE full profile BOM, adding Security.
 
Usage
-----

To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
               <groupId>org.wildfly.bom</groupId>
               <artifactId>jboss-javaee-7.0-with-security</artifactId>
               <version>9.0.0.Beta2</version>
               <type>pom</type>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>