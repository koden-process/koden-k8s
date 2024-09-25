# Déploiement de Wordpress

Utilisation de helm chart de Bitnami pour déployer wordpress.
https://bitnami.com/stack/wordpress/helm

```sh
helm install my-release oci://registry-1.docker.io/bitnamicharts/wordpress -f values.yaml --namespace koden
```