### Cert-manager
NGF 의 cert-manager 설정을 위한 기본 설치 
- Installation
```shell
kubectl apply -f https://github.com/cert-manager/cert-manager/releases/latest/download/cert-manager.yaml
```

- checking
```shell
kubectl get pods -n cert-manager
```