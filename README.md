# Kind-Helm-CircleCI-build
"helm deployed, kind owned, circleci stored concept"<br>

![image](https://user-images.githubusercontent.com/80027170/220209024-6570349f-105b-4765-b5c4-f66433321876.png) ![image](https://user-images.githubusercontent.com/80027170/220208870-fa4ca514-7500-4851-98c7-cb4a64c86692.png) ![image](https://user-images.githubusercontent.com/80027170/220208963-57382237-f168-4ef3-ba43-55ea2660f423.png) 



- using the circle ci docker execution environment - https://circleci.com/docs/using-docker/ <br>
- install the kubernetes in a container implementation at kind - https://kind.sigs.k8s.io/<br>
- connect a jump box to a docker network that can talk to the cluster in the execution env - https://docs.docker.com/network/<br>
- install the helm package manager in the jump box - https://helm.sh/<br>
- apply  a chart containing an application and its dependencies to run comprihensive security testing 🎉 <br>
- all within a circle ci with no deployment infrastructure. 


## Example
The test tomcat helm chart is showing in the kind kubernetes cluster
![image](https://user-images.githubusercontent.com/80027170/220207169-88ce2823-263f-4c1b-ad10-23608c78fb75.png)
