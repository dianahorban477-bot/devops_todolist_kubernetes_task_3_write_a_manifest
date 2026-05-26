# The instruction how to run and test ToDo-app in Kybernetes

## 1. How to use all manifests
For running all components in cluster execute next commands from the root of the project:
```bash
kubectl apply -f .infrastructure/namespace.yml
kubectl apply -f .infrastructure/busybox.yml
kubectl apply -f .infrastructure/todoapp-pod.yml