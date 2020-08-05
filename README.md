# properties-repository

This repository is for providing property files for Microservices.  
Microservice are reading property files via spring boot cloud config server applications.

#
- `<microservice-name>.yml` - This pattern of property file will be read by respective **`<microservice>`** for **default** profile. 
- `<microservice-name>-<profile>.yml` - This pattern of property file will be read by respective **`<microservice>`** for respected **`<profile>`**.
- `application.yml` - This property file will be read by **all microservices** for **all profiles**.
