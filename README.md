# my-keyfactor
https://www.ejbca.org/case/clean-up-microk8s-cluster-and-redeploy-ejbca-with-helm/
https://docs.keyfactor.com/container/latest/ejbca/get-started-with-ejbca-using-kubernetes-and-helm

```
# To deploy an ephemeral EJBCA Community test instance using Helm:
helm install ejbca --set fullnameOverride=ejbca \
    oci://repo.keyfactor.com/charts/ejbca-ce 
```


https://hub.docker.com/u/keyfactor


This demonstrated how you can get EJBCA up and running in a Kubernetes cluster for quick tests and demos. For real-world use cases, you need to configure integrations with an external database, an HSM, set up TLS, choose the method for exposing EJBCA to other applications and/or the outside world and more.
