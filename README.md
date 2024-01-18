# principios_kuberneste

kind create cluster
apt  install kubectl

sudo snap install kubectl --classic
kubectl cluster-info --context kind-kind

kubectl apply -f pod.yaml
kubectl get pod
kubectl delete replicaset nginx-replicaset
kubectl port-forward svc/nginx 80:80
kubectl apply -f service.yaml service/nginx created