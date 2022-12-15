Make sure you enable Kubernetes in Docker Desktop before running the commands below.

Deploy resource specified in the client-pod.yaml config file:

`kubectl apply -f client-pod.yaml`

Display information:

`kubectl get pods`

`kubectl get services`

`kubectl get deployments`

Show image information for a pod:

`kubectl describe pod client-pod`

Change the image used by the containers in a deployment:

`kubectl set image deployment/client-deployment client=stephengrider/multi-client:v2`
