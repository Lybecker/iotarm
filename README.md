# Deploy to Azure

Deploys:
 - IoT Hub
 - Azure Function (Java) with dynamic hosting plan (only paying for actual execution)

[![Deploy to Azure](https://azuredeploy.net/deploybutton.svg)](https://azuredeploy.net/)

Azure Deploy Button [special parameter names](https://elliotthamai.wordpress.com/2014/11/15/using-custom-arm-templates-with-the-deploy-to-azure-button/).

## Deploy via Azure CLI

```bash
az group create --name <name of ressource group> --location="North Europe"
az group deployment create --template-file azuredeploy.json --group <name of ressource group>
```
