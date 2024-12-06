# Installing a multi-repo Application

This repository is designed to work in tandem with the repo: https://github.com/chrisf-aarnet/mock-customers

To add the application to an existing install of ArgoCD just run the following command to create the kind Application in the argocd namespace.

```shell
kubectl apply -n argocd -f ArgoApplicationMultiRepo.yaml
```

When iterating you can delete using the following:

```shell
kubectl delete -n argocd -f ArgoApplicationMultiRepo.yaml
```
