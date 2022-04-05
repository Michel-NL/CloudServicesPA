# Cloud Services Steps

Provision Azure CLI to work with AKS and perform the actions to work with Kubernetes

## Azure CLI

Perform the steps to install azure-cli

Then login:

    az login

Follow the instructions in the new browser window.

Then retrieve cluster credentials:

    az aks get-credentials --resource-group $(resource group) --name $(Kubernetes name)

You are now able to perform commands against the Kubernetes API.

## Documentation

See the Azure CLI and Kubernetes documentation which provides steps to perform to manage AKS.

- [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)
- [Kubernetes](https://kubernetes.io/docs/tasks/tools/)

