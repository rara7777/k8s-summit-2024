## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add rara7777-k8s-summit-2024/myapi https://rara7777.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages.  You can then run `helm search repo rara7777-k8s-summit-2024/myapi` to see the charts.

To install the myapi chart:

    helm install rara7777-myapi rara7777-k8s-summit-2024/myapi

To uninstall the chart:

    helm delete rara7777-myapi
