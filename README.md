# Hello World - GitOps

This projects runs a minimal (Build & Deploy) GitOps-style pipeline. The deployment updates the manifests in [another manifest project](https://gitlab.com/gitlab-examples/ops/gitops-demo/k8s-agents).

This project is intended to be minimal to showcase the required setup using the GitLab Agent for Kubernetes for pull-based deployments. The code required lives in this repo, in the [`.gitlab-ci.yml`](.gitlab-ci.yml) and in the agent configuration project [after line 40 of its `.gitlab-ci.yml`](https://gitlab.com/gitlab-examples/ops/gitops-demo/k8s-agents/-/blob/main/.gitlab-ci.yml#L40)
