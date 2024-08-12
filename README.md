# Open Pages - Helm chart

Helm chart for deploying Open Pages to Kubernetes. See [Open Pages](https://github.com/kerniee/open-pages) repo for more information.

## Deploy

```shell
helm repo add open-pages https://kerniee.github.io/open-pages-helm
helm install open-pages/open-pages --generate-name -n open-pages
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
