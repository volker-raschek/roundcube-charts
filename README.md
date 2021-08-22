# roundcube-charts

[![Build Status](https://drone.cryptic.systems/api/badges/volker.raschek/roundcube-charts/status.svg)](https://drone.cryptic.systems/volker.raschek/roundcube-charts)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/volker-raschek)](https://artifacthub.io/packages/search?repo=volker-raschek)

This is an inofficial helm chart for
[roundcube](https://github.com/roundcube/roundcubemail), because it is not yet
an official helm chart available.

This helm chart can be found on [artifacthub.io](https://artifacthub.io/) and
can be installed via helm.

```bash
helm repo add volker.raschek https://charts.cryptic.systems/volker.raschek
helm install drone volker.raschek/roundcube
```

## Customization

All [configuration
options](https://github.com/roundcube/roundcubemail-docker/blob/master/README.md#configurationenvironment-variables)
can be defined in the `values.yml` file below the `config` section.
Alternatively can be the options passed via the `--set` flag of the `helm
install` command.
