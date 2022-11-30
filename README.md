# kubernetes-testing

`set-alias k -value kubectl` #sets alias for kubectl<br>
`kubectl apply -f ./dashboard-adminuser.yaml`  #needed to apply this yaml to create admin user<br>
`kubectl describe secret -n kube-system` #not sure what this is for, supposed to get your bearer token.<br>
`kubectl proxy` #runs your kubernetes dashboard UI<br>
`kubectl -n kubernetes-dashboard create token admin-user` #actually gets yours bearer token<br>
