# Github Actions Workflows

## Deployed Actions

| Category | File | Description | Trigger |
|----------|------|-------------|---------|
| Tests | [backend-test.yaml](backend-test.yaml) | runs backend tests | push (#backend-test) |
| Tests | [lint.yaml](lint.yaml) | runs linting on code changes | on merge requests |
| Tests | [secret-scan.yaml](secret-scan.yaml) | runs secret scanning on code changes | on merge requests & push |
| Deploy | [changelog.yaml](changelog.yaml) | creates a new release | on merge requests |
| Deploy | [frontpage-deploy.yaml](frontpage-deploy.yaml) | Deploys frontpage | manual deploy |
| Deploy | [manual-deploy.yaml](manual-deploy.yaml) | Deploys backend & frontend | manual deploy |