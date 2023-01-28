# skaffold-issue

The profile kubernetes deployment is not deploying when here are requires stanza. This is found in <prjectRoot>/skaffold.yaml 

1. skaffold render -p dev
2. skaffold dev -p dev  -vdebug
3. kubectl get po -w