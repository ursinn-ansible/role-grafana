# Ansible Role - Grafana

[![GitHub last commit](https://img.shields.io/github/last-commit/ursinn-ansible/role-grafana?logo=github&style=for-the-badge)](https://github.com/ursinn-ansible/role-grafana/commits)
[![License](https://img.shields.io/github/license/ursinn-ansible/role-grafana?style=for-the-badge)](https://github.com/ursinn-ansible/role-grafana/blob/main/LICENSE)

Docker Image: https://hub.docker.com/r/grafana/grafana-enterprise

## Options

| Option | Default Value |
| ---- | ---- |
| role_grafana_image | docker.io/grafana/grafana-enterprise |
| role_grafana_container | grafana |
| role_grafana_volume | grafana |
| role_grafana_network | app-network |
| role_grafana_tmp_dir | /tmp/ansible-role-grafana |
| role_grafana_config_metrics_basic_auth_username | |
| role_grafana_config_metrics_basic_auth_password | |
| role_grafana_config_auth_signout_redirect_url | |
| role_grafana_config_auth_oauth_auto_login | false |
| role_grafana_config_auth_generic_oauth_name | OAuth |
| role_grafana_config_auth_generic_oauth_enabled | false |
| role_grafana_config_auth_generic_oauth_client_id | some_id |
| role_grafana_config_auth_generic_oauth_client_secret | some_secret |
| role_grafana_config_auth_generic_oauth_scopes | user:email,read:org |
| role_grafana_config_auth_generic_oauth_auth_url | https://foo.bar/login/oauth/authorize |
| role_grafana_config_auth_generic_oauth_token_url | https://foo.bar/login/oauth/access_token |
| role_grafana_config_auth_generic_oauth_api_url | https://foo.bar/user |
| role_grafana_config_auth_generic_oauth_role_attribute_path | |
| role_grafana_datasource_prometheus_url | http://prometheus:9090 |
| role_grafana_datasource_prometheus_basicAuth | false |
| role_grafana_datasource_prometheus_basicAuthUser | |
| role_grafana_datasource_prometheus_basicAuthPassword | |
| role_grafana_datasource_loki_url | http://loki:3100 |
| role_grafana_datasource_loki_basicAuth | false |
| role_grafana_datasource_loki_basicAuthUser | |
| role_grafana_datasource_loki_basicAuthPassword | |

## License

This project is under the MIT License. See the [LICENSE](https://github.com/ursinn-ansible/role-grafana/blob/main/LICENSE) file for the full license text.
