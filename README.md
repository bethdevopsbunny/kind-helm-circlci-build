# Kind-Helm-CircleCI-build
"helm deployed, kind owned, circleci stored concept"

- using the circle ci docker execution environment - https://circleci.com/docs/using-docker/ <br>
- install the kubernetes in a container implementation at kind - https://kind.sigs.k8s.io/<br>
- connect a jump box to a docker network that can talk to the cluster in the execution env - https://docs.docker.com/network/<br>
- install the helm package manager in the jump box - https://helm.sh/<br>
- apply  a chart containing an application and its dependencies to run comprihensive security testing 🎉 <br>
- all within a circle ci with no deployment infrastructure. 


## Example
The test tomcat helm chart is showing in the kind kubernetes cluster
![image](https://user-images.githubusercontent.com/80027170/220207169-88ce2823-263f-4c1b-ad10-23608c78fb75.png)
