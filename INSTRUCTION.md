./bootstrap.sh

kubectl get pods
kubectl get pods -n todoapp
kubectl exec todoapp-1 -n todoapp -- ls /app/configs
kubectl exec todoapp-1 -n todoapp -- ls /app/secrets
