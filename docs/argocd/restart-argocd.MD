kubectl rollout restart deployment argocd-server -n argocd

When this is usefull:
After add the argocd-argocd-ingress.yaml file and the argocd-server-insecure-configmap.yaml file, you need to restart the argocd-server deployment to apply the changes.