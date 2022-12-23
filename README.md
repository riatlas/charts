# Helm charts
Riatlas helm chart repository

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add riatlas https://riatlas.github.io/charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
robyrobot` to see the charts.

To install the kubernetes-zerotier-bridge chart:

    helm install my-zerotier-bridge riatlas/kubernetes-zerotier-bridge

To uninstall the chart:

    helm uninstall my-zerotier-bridge

NOTE: remember to create a value.yaml replacing zerotier config value with the correct ones 

## Helm charts list
* **[kubernetes-zerotier-bridge](https://github.com/riatlas/charts/tree/main/charts/kubernetes-zerotier-bridge)**
* **[postgresql-migration](https://github.com/riatlas/charts/tree/main/charts/postgresql-migration)**
* **[elasticsearch-migration](https://github.com/riatlas/charts/tree/main/charts/elastic-migration)**
