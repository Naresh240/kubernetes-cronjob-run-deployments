# kubernetes-cronjob-run-deployments

# Minikube cluster setup
  [minikube](https://github.com/Naresh240/kubernetes/tree/main/minikube-setup)
# Create configmap with below command
````
  kubectl create configmap nginx-configmaps --from-file=deploment.yml
````
# Create run service account file
````
  kubectl apply -f service-account.yml
````
# Run cron job by specifing cron expression
````
  kubectl apply -f cronjob.yml
````
