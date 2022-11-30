# kubernetes-testing

`set-alias k -value kubectl` #sets alias for kubectl
`kubectl apply -f ./dashboard-adminuser.yaml`  #needed to apply this yaml to create admin user
`kubectl describe secret -n kube-system` #not sure what this is for, supposed to get your bearer token.
`kubectl proxy` #runs your kubernetes dashboard UI
`kubectl -n kubernetes-dashboard create token admin-user` #actually gets yours bearer token
