# ELK Helm Chart

This Helm chart is a build for Elasticsearch Kibana deployment based on ECK Operator. Before using this chart make sure you have ECK operator deployed in cluster.



**Note**: Please test it throughly before use.


## REQUIREMENTS

* [Helm][] >=3.0.0

* Kubernetes >=1.8



### HEALTH CHECK

*echo "Health:`kubectl get elasticsearch elasticsearch -n dev -o=jsonpath='{.status.health}'`" > test

*echo "Nodes:`kubectl get elasticsearch elasticsearch -n dev -o=jsonpath='{.status.availableNodes}'`" >> test

*echo "Phase:`kubectl get elasticsearch elasticsearch -n dev -o=jsonpath='{.status.phase}'`" >> test
