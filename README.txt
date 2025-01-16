cat ~/.kube/config >> ~/minikube.yaml
kubectl --kubeconfig minikube.yaml get namespaces
kubectl --kubeconfig minikube.yaml -n default get pods