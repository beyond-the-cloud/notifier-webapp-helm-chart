# notifier-webapp-helm-chart

Notifier Web App Helm Chart GitHub Repository Setup

Install the helm:

```bash
helm install --set dbHost=dbHost --set dbPassword=dbPassword {{ .Release.Name }} ./{{ .Chart.Name }}
```

Uninstall the helm:
`helm uninstall {{ .Release.Name }}`

Check NOTES.txt for more details.