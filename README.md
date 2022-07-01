# Chart Repository

helm chart 仓库

## Alias URL

Default: http://fimreal.github.io/chart_repository

CNAME with cf CDN : https://helm.epurs.com/

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add fimreal https://helm.epurs.com/helm-charts # suggested

or

    helm repo add fimreal http://fimreal.github.io/chart_repository

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
fimreal` to see the charts.

To install the <chart-name> chart:

    helm install my-<chart-name> fimreal/<chart-name>

To uninstall the chart:

    helm delete my-<chart-name>
