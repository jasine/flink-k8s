# flink on kubernetes

## useage

- please config nfs address or change volume type of statefulset(job-manager and task-manager)

- please config job manager service type (LoadBalancer by default)

- replace the image tag of flink to `1.6-hadoop28` if you use HDFS

## what's more

- job-manager has one pod
- task-manager has three pod by default
