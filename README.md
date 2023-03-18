# Secure Supply Chain Demo

## 1. Install OpenShift GitOps Operator

```
oc apply -k https://github.com/pittar-demos/demo-catalog/openshift-gitops-operator/overlays/gitops-1.7
```

## 2. Bootstrap "nonprod" Cluster

```
oc apply -k https://github.com/pittar-demos/secure-supply-chain/00-bootstrap/nonprod
```
