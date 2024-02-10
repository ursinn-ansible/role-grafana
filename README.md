# Ansible Role - Grafana

[![GitHub last commit](https://img.shields.io/github/last-commit/ursinn-ansible/role-grafana?logo=github&style=for-the-badge)](https://github.com/ursinn-ansible/role-grafana/commits)
[![License](https://img.shields.io/github/license/ursinn-ansible/role-grafana?style=for-the-badge)](https://github.com/ursinn-ansible/role-grafana/blob/main/LICENSE)

Docker Image: https://hub.docker.com/r/grafana/grafana-enterprise

## Options

| Option | Default Value |
| ---- | ---- |
| app_grafana_docker_volume_config | grafana_config |
| app_grafana_docker_volume_data | grafana_data |
| app_grafana_docker_image | docker.io/grafana/grafana-enterprise |
| app_grafana_docker_container | grafana |
| app_grafana_docker_network | app-network |
| app_grafana_tmp_dir | /tmp/ansible-role-grafana |
| app_grafana_prometheus_url | http://prometheus:9090 |
| app_grafana_prometheus_basicAuth | false |
| app_grafana_prometheus_username | |
| app_grafana_prometheus_password | |
| app_grafana_loki_url | http://loki:3100 |
| app_grafana_loki_basicAuth | false |
| app_grafana_loki_username | |
| app_grafana_loki_password | |
| app_grafana_metrics_username | |
| app_grafana_metrics_password | |

## License

This project is under the MIT License. See the [LICENSE](https://github.com/ursinn-ansible/role-grafana/blob/main/LICENSE) file for the full license text.
