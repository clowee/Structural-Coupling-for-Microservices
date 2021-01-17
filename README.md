# Structural-Coupling-for-Microservices


This is the repository to share the raw data and the replication script for the paper "Structural Coupling for Microservices" 


# Raw Data

* File xxx contains ... 
* FIle yyy contains

# Requirements

Java jdk8 or higher.

# Replication

To replicate our work, please folow this steps: 

1. Download the MicroDepGraph tool [download here](https://github.com/clowee/MicroserviceDataset/archive/1.0.zip)
2. clone a git repository containing a java project developed with a micorservice architectural style.
3. execute MicroDepGraph as:     java -jar microservices-dependency-check.jar  <absolute_path_of_the_microservice_project> <project_name> 

An example command to run the tool from command line is,
 java -jar microservices-dependency-check.jar /home/myuser/ftgo-application-master ftgo-application-master
