# Openshift Compliance Operator


```
oc project openshift-compliance

oc get profiles.compliance

oc get profiles.compliance rhcos4-e8

oc get rules

oc get scansettings

oc get scansettings default -o yaml

oc get scansettings default-auto-apply -o yaml


oc compliance -h

oc compliance bind --name moderate profile/ocp4-moderate profile/rhcos4-moderate --dry-run
oc compliance bind --name moderate profile/ocp4-moderate profile/rhcos4-moderate -S default-auto-apply

oc get scansettingbindings
oc get compliancesuites
oc get pods
oc get compliancesuites
oc get compliancecheckresults


oc logs -f <pod> -c scanner



```
