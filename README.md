# openshift-pipelines-workshop
Workshop to demonstrate OpenShift Pipelines (featuring Tekton)

## Link below
https://redhat-developer-demos.github.io/openshift-pipelines-workshop/


```bash
oc adm policy add-scc-to-user anyuid -z pipeline -n pipelines-rheledge
oc adm policy add-role-to-user admin system:serviceaccount:pipelines-rheledge:pipeline -n pipelines-rheledge
```