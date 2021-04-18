# eks
A selection of scripts, docs for eks

To run an ubuntu pod and use it for debugging, run following commands:

Create teh pod

> kubect apply -f https://raw.githubusercontent.com/prabhatsharma/eks/master/debug-pod.yaml


exec into the pod

> kubectl exec -it ubuntu -- sh

