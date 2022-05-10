[![javadoc-master](https://img.shields.io/badge/Javadoc-master-green?style=plastic)](https://autostreams.github.io/prototype-utils/javadoc/)
[![javadoc-develop](https://img.shields.io/badge/Javadoc-develop-green?style=plastic)](https://autostreams.github.io/prototype-utils/javadoc-develop/)

## About The Project
This is the utilities used by the Autostreams [Pulsar](https://github.com/AutoStreams/prototype-pulsar) and [Kafka](https://github.com/AutoStreams/prototype-kafka) prototypes. The Pulsar and Kafka prototypes uses this repository as a Maven dependency defined in their pom.xml files. 

## Getting Started
First acquire this project by cloning the repository. Cloning this repository can be done by downloading [Git](https://git-scm.com/) then executing the command:
```bash
git clone https://github.com/AutoStreams/prototype-utils.git
```
The following section explains how to build the project.

### Build with Maven
**Prerequisites**
* Download the latest version of [Maven](https://maven.apache.org/).
* Download a Java JDK of version 17
* Set the working directory to the root of this Pulsar prototype producer project which is **`prototype-utils/`**

To build the project execute the command:
```bash
mvn package
```
