#After creating the service, I entered the container of pod using the following command
kubectl run -i --tty <container-name> --image=busybox

#Then in pod-containaer I executed the following command
nslookup exname-svc
