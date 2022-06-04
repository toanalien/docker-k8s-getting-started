DOCKER-K8S-GETTING-STARTED
----

```bash
$ kubectl apply -f tutorial.yaml
service/tutorial created
deployment.apps/tutorial created
```

```bash
$ kubectl get svc
NAME       TYPE   	CLUSTER-IP     EXTERNAL-IP   PORT(S)       AGE
kubernetes ClusterIP  	10.96.0.1      <none>        443/TCP       118m
tutorial   LoadBalancer 10.98.217.243  localhost     80:31575/TCP  12m
```