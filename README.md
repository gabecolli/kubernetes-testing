# kubernetes-testing
`code`
set-alias k -value kubectl
`code`
kubectl apply -f ./dashboard-adminuser.yaml


kubectl describe secret -n kube-system

kubectl proxy

kubectl -n kubernetes-dashboard create token admin-user
