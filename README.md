# learn-flux

## install flux cli
- https://fluxcd.io/docs/installation/
- flux cli 
```bash 
curl -s https://fluxcd.io/install.sh | sudo bash
```

## bootstrap 
- https://fluxcd.io/docs/installation/#github-and-github-enterprise
```bash
export GITHUB_TOKEN=<your gh personal token>
flux bootstrap github --owner=gnmahanth --repository=learn-flux --path=clusters/minikube --personal
```