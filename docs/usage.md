# How to use this project

```bash
task setup
```

## multipass

```bash
task multipass:setup
task multipass:launch:k8s:master
task multipass:launch:k8s:node
task multipass:make:certificates
task multipass:launch:traefik
task crossplane:apply
task k8s:apply:all
```

## minikube

```bash
task minikube:setup
task minikube:apply:all
```

### Mount Path

```bash
task minikube:mount
```
