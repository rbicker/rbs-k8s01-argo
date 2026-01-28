# rbs-k8s01-argo

## argocd

```bash
k -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d
```

## sops

```bash
export SOPS_AGE_KEY=$(bw get password 735cfec3-d1d9-4494-bbad-791d6ec433ae)

```