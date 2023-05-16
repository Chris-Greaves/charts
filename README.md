# Charts

Repo containing Helm Charts I've created and loosly maintain. 

## Usage

[Helm](helm.sh) must be installed before using any charts, see the [docs](https://helm.sh/docs/intro/quickstart/).

Run the following Helm command to add the repo:

```bash
helm repo add cg-stable https://chris-greaves.github.io/charts/
```

You can then run `helm search repo cg-stable` to see the charts.

for incubator charts run this command:

```bash
helm repo add cg-incubator https://chris-greaves.github.io/charts/incubator/
```

And search with `helm search repo cg-stable`.