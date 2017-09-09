# Jersey_Demo

A demo for a java-based framework used for developing RESTful Web services

- A demo project making use of Jersey 2.x (a Java-based Web-services framework for developing RESTful Web Services that implements JAX-RS API)
- Built using maven
- Deployed on Apache Tomcat 8.5 web container

In case of a ClassNotFoundException with org.glassfish.jersey.servlet.ServletContainer exception while deploying on Apache Tomcat, take the
following steps:

Right click on the eclipse project -> Properties -> Deployment Assembly -> Add -> Java Build Path Entries -> Maven Dependencies -> Finish.

