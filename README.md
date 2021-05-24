# fleet-app-of-apps

## Description

This repo has some gitrepo deployment files for Rancher Fleet

### Manual Deploy

Run this on the Rancher control cluster to deploy all the gitrepos to cluster group.

```kubectl apply -f bill-group ```

### Argo CD Deploy

You can install Argo CD on the Rancher controller and have it point to the fleet-bill and fleet-bob
directory recursively.
