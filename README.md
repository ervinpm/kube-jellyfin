# Jellyfin for Kubernetes

Configuration to spin up jellyfin into your kubernetes cluster

## How to use
```sh
$ kubectl -f deployment.yaml -f pvc.yaml -f service.yaml -f ingress.yaml
```

## Dependencies

Required to have managed nfs storage
