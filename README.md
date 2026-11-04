# EKS CI/CD Pipeline Lab (AWS CodePipeline + CodeBuild + ECR + EKS)

Ye repository AWS CodePipeline aur CodeBuild ke zariye Amazon EKS par automated deployment ke liye hai.

## Files Included
- `index.html`: Sample web application (Version 1.0)
- `Dockerfile`: Nginx container image banane ke liye
- `k8s-deployment.yaml`: Kubernetes Deployment (2 replicas) aur LoadBalancer Service
- `buildspec.yml`: AWS CodeBuild ke instructions (Docker build, ECR push, aur `kubectl apply`)
