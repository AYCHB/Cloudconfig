# Spring Cloud Config Server

##Objective:
 * Maintain centralized configuration data(or application properties) of applications in GIT
 * Provide webservices to programmatically read centralized configuration data
 * Authenticate different groups to update configuration information

##Users roles:
 * Engineer – Creates new configuration file for Application-Environment combination
 * Application lead – Edits an existing configuration file
 * Application developer – View existing configuration file

##Support services features:
 * Spring cloud config ![https://cloud.spring.io/spring-cloud-config/img/spring-logo.png] (https://cloud.spring.io/spring-cloud-config/img/spring-logo.png)
 * Zookeeper ![https://zookeeper.apache.org/images/zookeeper_small.gif](https://zookeeper.apache.org/images/zookeeper_small.gif)
 * Supports externalized configuration in a distributed environment
 * HTTP, resource-based API for external configuration (key-value pairs, or equivalent YAML content)
 * Encrypt and decrypt property values (symmetric or asymmetric)

##References:
 * https://cloud.spring.io/spring-cloud-config/spring-cloud-config.html
