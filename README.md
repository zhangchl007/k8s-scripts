# k8s-scripts

1. Please update the file: clear-completed-jobs.yaml based on your actual situation  

2. create a test pod, alias kc=kubectl

```
kc apply -f jobs.yaml

```
3. apply this clear up jobs
```
kc apply -f jobs_rbac.yaml
kc apply -f clear-completed-jobs.yaml

```

