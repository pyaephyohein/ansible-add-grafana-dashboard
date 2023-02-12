## Add dashboard to grafana
### When you run in local machine
1. Please Add grafana ```url``` and  ```api_key``` to [all.yaml](group_vars/all.yaml)
2. Add Your customized dashboards (filename.json) to [files](roles/add_grafana_dashboard/files)
3. Run ```ansible-playbook -v run.yaml```

### When you run with gitlab CI
1. Please Add Grafana ```GRAFANA_URL``` and ```GRAFANA_API_KEY``` to Gitlab CI variable
2. Add Your customized dashboards (filename.json) to [Dashboards](Dashboards)

