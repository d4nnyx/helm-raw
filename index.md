[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add helm-raw https://d4nnyx.github.io/helm-raw

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
helm-raw` to see the charts.

To install the helm-raw chart:

    helm install my-release-name helm-raw/helm-raw

To uninstall the chart:

    helm delete my-release-name