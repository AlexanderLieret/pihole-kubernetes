# mojo2600.github.io
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

[Helm](https://helm.sh) repo for different charts which can be installed on [Kubernetes](https://kubernetes.io)

Further documentation including chart keys, types, and default values is at https://hub.helm.sh/charts/mojo2600/pihole

### Add Helm repository

To install the repo just run:

```bash
helm repo add mojo2600 https://mojo2600.github.io/pihole-kubernetes/
helm repo update
```

### Helm Charts

* [pihole](https://mojo2600.github.io/pihole-kubernetes)

  ```bash
  helm install --name your-release mojo2600/pihole
  ```
  

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://www.mojo2k.de"><img src="https://avatars1.githubusercontent.com/u/2462817?v=4" width="100px;" alt=""/><br /><sub><b>Christian Erhardt</b></sub></a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!