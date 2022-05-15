# observability-infra

Deploys an observability infrastructure in k8s, with the help of helm charts and helmfile.  
For a quickstart, copy and modify `.env.sample.yaml` to `.env.default.yaml` and run `helmfile apply`.

## Notes

If you encounter 'no matches for kind' errors when applying helmfile,
use `--skip-diff-on-install` flag to bypass initial diff when running apply:
```
helmfile apply --skip-diff-on-install
```
