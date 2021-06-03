# wordpress-k8-pv 
# Here I have documented the steps to reproduce
kubectl create -f secret.yml <br>
kubectl create -f pv.yml <br>
kubectl create -f claim.yml <br>
kubectl create -f mysqlpv.yml <br>
kubectl create -f sqldeploy.yml <br>
kubectl create -f wp.yml <br>
