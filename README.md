# Barracuda CloudGen WAN for Azure - Log Analytics Workspace

## Introduction
The contents here are intended to improve the reporting avaialable for the Barracuda CloudGen WAN.  They provide basic information on;

- VPN Status
- Device Availabilty
- Device Performance
- Device Bandwidth
- WAN Latency

This template will deploy a workbook into a new or existing Log Analytics workspace




## Deployment

### Deployment

#### Quick Deploy
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FFelixBman%2FAzureCGWWorkbook%2Fmain%2Fazuredeploy.json" target="_blank"><img src="http://azuredeploy.net/deploybutton.png"/></a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FFelixBman%2FAzureCGWWorkbook%2Fmain%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
### Azure Portal for Workbooks only

To manually deploy a workbook via Azure Portal;

- Open https://portal.azure.com
- Navigate to Log Analytics workspaces
- Select your chosen workspace
- From the menu on the left, select Workbooks
- Create New
- Click on the Advanced Editor button ![Enable Firewall Activity Log](images/advancedcode.png)
- Open the ![Workbook](CGW.workbook) in Raw mode and copy and paste the contents between GitHub and the editor in the Azure portal
- Click on the Apply button. Click on the Advanced Editor button ![Apply](images/paste.png)# AzureCGWWorkbook
