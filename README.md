# knative-exploration
My personal repository on learning Knative


Run bash commands
```bash
kubectl apply -f extensions/knative-serving/

kubectl apply -f extensions/knative-eventing/

kubectl apply -k extensions/

kubectl apply -k server/

kubectl wait kafka/my-cluster --for=condition=Ready --timeout=300s -n knative-eventing

kubectl apply -k eventing/

kubectl get pods -n knative-eventing | grep ibm

kubectl port-forward ibm-mq-server-{POD ID} 9443 -n knative-eventing

```