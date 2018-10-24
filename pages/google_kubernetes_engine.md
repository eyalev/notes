
# Google Kubernetes Engine

## Available Versions

The cluster versions available in GKE are not the newest Kubernetes versions that have been
released.

The new versions are available as 
[Alpha Clusters](https://cloud.google.com/kubernetes-engine/docs/concepts/alpha-clusters) 
and after some time become available for general use.

## Specifying cluster version in `gcloud containers clusters create` 

- https://cloud.google.com/kubernetes-engine/versioning-and-upgrades#specifying_cluster_version
  - > When you create or upgrade a cluster using gcloud, you can specify a cluster version using the --cluster-version flag. You can use a specific version, such as 1.9.7-gke.N. You can also use a version alias:
      <br><br>
      latest: Specifies the highest supported Kubernetes version currently available on GKE in the cluster's zone or region.<br><br>
      1.X: Specifies the highest valid patch+gke.N patch release in the 1.X minor version<br><br>
      1.X.Y: Specifies the highest valid gke.N patch in the 1.X.Y patch release.
- https://cloud.google.com/sdk/gcloud/reference/container/clusters/create
- https://cloud.google.com/kubernetes-engine/release-notes
  - Includes latest version updates.

