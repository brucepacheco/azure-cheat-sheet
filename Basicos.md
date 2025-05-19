# Azure Cheat Sheet | Comandos Básicos

## Comandos de Azure CLI

### Autenticación
```bash
az login
```
### Listar recursos
```bash
az resource list
```
### Crear grupo de recursos
```bash
az group create --name MyResourceGroup --location eastus
```
### Crear maquina virtual
```bash
az vm create --resource-group MyResourceGroup --name MyVm --image UbuntuLTS
```
### Obtener información de una maquina virtual
```bash
az vm show --resource-group MyResourceGroup --name MyVm
```
### Eliminar grupo de recursos
```bash
az group delete --name <nombre_del_grupo> --yes --no-wait
```