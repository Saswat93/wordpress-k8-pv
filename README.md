# wordpress-k8-pv 
Here I have documented the steps to reproduce
kubectl create -f secret.yml 
kubectl create -f pv.yml
kubectl create -f claim.yml
kubectl create -f mysqlpv.yml
kubectl create -f sqldeploy.yml
kubectl create -f wp.yml
