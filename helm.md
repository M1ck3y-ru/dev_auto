Commandes utilisées
Installation NGINX Ingress
helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx
helm repo update
helm install ingress-nginx ingress-nginx/ingress-nginx

Installation Kubecost
helm repo add kubecost https://kubecost.github.io/cost-analyzer/
helm repo update
helm install kubecost kubecost/cost-analyzer --namespace kubecost --create-namespace
cost-analyzer
Kubecost
Helm tarball repository for Kubecost product