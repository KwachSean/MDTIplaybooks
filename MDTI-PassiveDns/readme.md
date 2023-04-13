# MDTI-PassiveDns

## Overview

## Prerequisites
1. This playbook inherits API connections created and established within a base playbook. Ensure you have deployed [MDTI-Base](https://raw.githubusercontent.com/Azure/Azure-Sentinel/master/Solutions/Microsoft%20Defender%20Threat%20Intellingence/Playbooks/MDTI-Base/azuredeploy.json) this playbook. If you have trouble accessing your account or your credentials contact your account representative or reach out to discussMDTI[@]microsoft.com.
2. This playbook requires "Microsoft Sentinel Contributor" role to update Incidents.


## Deployment


<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FKwachSean%2FMDTIplaybooks%2Fmain%2FMDTI-PassiveDns%2FMDTI-PassiveDns.json"
target="_blank">
    <img src="https://aka.ms/deploytoazurebutton"/>
</a>
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FKwachSean%2FMDTIplaybooks%2Fmain%2FMDTI-PassiveDns%2FMDTI-PassiveDns.json"
target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.png"/>
</a>

## Post-Deployment Instructions
After deploying the playbook, you must authorize the connections leveraged.

1. Visit the playbook resource.
2. Under "Development Tools" (located on the left), click "API Connections".
3. Ensure each connection has been authorized.

**Note: If you've deployed the [MDTI-Base](https://raw.githubusercontent.com/Azure/Azure-Sentinel/master/Solutions/Microsoft%20Defender%20Threat%20Intellingence/Playbooks/MDTI-Base/azuredeploy.json) playbook, you will only need to authorize the Microsoft Sentinel connection.**