```
oc get packagemanifest elasticsearch-operator -n openshift-marketplace -o jsonpath='{.status.channels[].name}'
```