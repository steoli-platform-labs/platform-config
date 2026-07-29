# platform-config

GitOps desired state for the platform. Bootstrap `bootstrap/root-application-dev.yaml` first; Lab 15 adds staging and production root Applications. Argo CD then reconciles child Applications from the environment paths under `clusters/`.
