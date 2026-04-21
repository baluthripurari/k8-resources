## K8 Resources  
Namespace --> Isolated project where you can create resources related to your application
#  - kubectl get namespace ---> Get a list of all namespaces in the cluster
#  - kubectl get namespace <namespace-name> ---> Get details of a specific namespace
# - kubectl create namespace <namespace-name> ---> Create a new namespace
# - kubectl delete namespace <namespace-name> ---> Delete a namespace
Pods --> Isolated container that runs an application
pods conatins mutiple containers . containers inside pod share same network and storage resources

# kubectl get pods
# kubectl get all
# kubectl describe pods
# kubectl get rs (or) kubectl get replicaset
# kubectl delete deployment
# kubectl get deployment
# kubectl describe rs
# kubectl delete replicaset 
# kubectl apply -f (yml file name)
# kubectl get svc (or) kubectl get service
# kubectl delete svc
# kubectl get ns (or) # kubectl get namespaces
