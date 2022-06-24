# canary-deployment
- kubectl apply -f deployment-primary.yaml
- kubectl apply -f deployment-canary.yaml
- kubectl apply -f myapp-service.yaml
- kubectl get svc myapp-service
# Checking Deployment
- ./test.sh
