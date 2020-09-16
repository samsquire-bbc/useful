# useful information

```
kafkacat -C -b kafka-uced-a:9092 -q -t repository.resource-provisioning -o 9000
```
Consume from kafka-uced-a:9092 quietly on topic repository-resource-provisioning at offset 9000

```
kubectl get pods | grep deployment name
```

# workflow

1. ./run-dev.sh
1. kubeconfig test
1. set-aws-credentials test
