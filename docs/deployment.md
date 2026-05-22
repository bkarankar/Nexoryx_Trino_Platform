# Deployment

kubectl apply -f kubernetes/

Verify:

kubectl get pods -n nexoryx-trino
kubectl get svc -n nexoryx-trino
kubectl get ingress -n nexoryx-trino
