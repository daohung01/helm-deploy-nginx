# Helm Charts from DAO HUNG.
Hi, I'm a DevOps engineer.

## Usage

Some common Helm commands for you

```
# Add repo before using
$ helm repo add daohung01 https://raw.githubusercontent.com/daohung01/charts/master/
"daohung01" has been added to your repositories

# Search for charts, or list all the charts by repo's name
$ helm search repo daohung01
NAME                	CHART VERSION	APP VERSION	DESCRIPTION
daohung01/ambassador-ssl	0.1.0        	1.0.0      	A Helm chart for Kubernetes

# Get configurations (values file)
$ helm show values daohung01/ambassador-ssl > myvalues.yaml

# Install chart with your configurations
$ helm install mywebsite-ssl daohung01/ambassador-ssl
```

## List of charts

- Ambassador-SSL : install Let's Encrypt certificate for your Ambassador API Gateway (Ambassaador Edge Stack)
- _(updating new chart here...)_
