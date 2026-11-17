# vprofile-helm
Helm chart for the vprofile app, deployed to EKS by Argo CD.

## Security note
The DB password in `kubedefs/secret.yaml` is a lab-only course default. In production I would keep it in a secrets manager.