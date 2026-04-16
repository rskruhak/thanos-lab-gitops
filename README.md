# thanos-lab-gitops

GitOps repository for the Thanos home lab OpenShift cluster.

## Structure

- `apps/` - Application deployments managed by ArgoCD
  - `nfs-provisioner/` - NFS Subdir External Provisioner
  - `cert-manager/` - Certificate management
  - `image-registry/` - OCP internal image registry config
- `cluster/` - Cluster-level configuration
  - `storage/` - Storage classes and PV configuration
  - `networking/` - Network configuration

## Cluster Details

- OCP Version: 4.20
- Cluster: ocp.lab.thanos.com
- ArgoCD: openshift-gitops-server-openshift-gitops.apps.ocp.lab.thanos.com
