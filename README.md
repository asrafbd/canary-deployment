# canary-deployment
- kubectl apply -f deployment-primary.yaml
- kubectl apply -f deployment-canary.yaml
- kubectl apply -f myapp-service.yaml
- kubectl get svc myapp-service
# Checking Deployment
- ./test.sh
- Both versions of the application are running. 10-20% of traffic will be routed to the new version.
