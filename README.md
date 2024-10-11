# DO101-apps

Apps for the DO101 course.

oc new-app --name version https://github.com/surfspiders/DO101x-apps#update-app --context-dir version

oc expose svc/version

oc get all --selector app=version
oc delete all --selector app=version
