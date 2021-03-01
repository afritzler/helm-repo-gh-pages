# helm-repo-gh-pages

Using Github Action to release helm chart via `gh-pages` and [helm releaser](https://github.com/helm/chart-releaser).

## Structure

The `charts` folder contains the corresponding helm charts which should be build and released. The `index.yaml` file is being pushed to the `gh-pages`.

```shell
.
├── README.md
└── charts
    └── hello
```

