# ELK Helm Chart

This Helm chart is a build on ELK operator based deployment. 

**Note**: Please test it throughly before use.


## Requirements

* [Helm][] >=3.0.0
* Kubernetes >=1.8
* Minimum cluster requirements include the following to run this chart with
default settings. All of these settings are configurable.
  * Three Kubernetes nodes to respect the default "hard" affinity settings
  * 1GB of RAM for the JVM heap

