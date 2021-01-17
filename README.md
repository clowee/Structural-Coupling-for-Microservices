# Structural-Coupling-for-Microservices


This is the repository to share the raw data and the replication script for the paper "Structural Coupling for Microservices" 


# Requirements

Java jdk8 or higher.

# Replication

To replicate our work, please folow this steps: 

1. Download the MicroDepGraph tool [download here](https://tuni-my.sharepoint.com/:u:/g/personal/mohammadimranur_rahman_tuni_fi/EV_IIoN5rxlKvFvCIxPQyPoBRKUsF_9lH-IC2QL3PZV0dA?e=c1PwWN)
2. clone a git repository containing a java project developed with a micorservice architectural style.
3. execute MicroDepGraph as:     java -jar microDepGraph.jar  <absolute_path_of_the_microservice_project> <project_name> 

An example command to run the tool from command line is,
 java -jar microDepGraph.jar /home/myuser/ftgo-application-master ftgo-application-master

# Raw Data

After analyzing the project, MicroDepGraph generates dependency graph as an svg image and GraphMl as well as different matrices in CSV files,

* An SVG file 
* CSV files containing different matrices i,e CBM, SC, Out degree, in degree, max degree and number of classes of each services
* GraphML file a common format for exchanging graph structure data
