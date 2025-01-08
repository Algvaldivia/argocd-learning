# argocd-learning
Deploy ArgoCD in Minikube Cluster to deploy applications and drive some tests with Crossplane

Create New Namespace
kubectl create namespace learning-argocd

kubectl get all -n learning-argocd

kubectl port-forward service/nginx-service 8088:80 -n learning-argocd