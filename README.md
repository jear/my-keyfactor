# my-keyfactor
https://docs.keyfactor.com/container/latest/ejbca/get-started-with-ejbca-using-kubernetes-and-helm

```
# To deploy an ephemeral EJBCA Community test instance using Helm:
helm install ejbca --set fullnameOverride=ejbca \
    oci://repo.keyfactor.com/charts/ejbca-ce 
```
