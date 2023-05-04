# Typosquat playbook 

## Overview

## Prerequisites
1. Access to Open squat API (https://rapidapi.com/atenreiro/api/opensquat1/), you will require access to the RAPID API Key , RAPID APRI -Host , you can sign up for a monthly quota trial in the link provided
2. Access to MDTI API , access to the logic app would be best through an Client App registration, details of that and how to do that can be found here : , you can also sign up for a trial for the API  and set up the client APP here :(https://techcommunity.microsoft.com/t5/microsoft-defender-threat/what-s-new-apis-in-microsoft-graph/ba-p/3780350)

## Deployment


<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FKwachSean%2FMDTIplaybooks%2Fmain%2FTyposquat(openSquat)
%2Fazuredeploy.json"
target="_blank">
    <img src="https://aka.ms/deploytoazurebutton"/>
</a>
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FKwachSean%2FMDTIplaybooks%2Fmain%2FTyposquat(openSquat)
%2Fazuredeploy.json"
target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.png"/>
</a>

## Post-Deployment Instructions
After deploying the playbook, you must authorize the connections leveraged.

1. Visit the playbook resource.
2. Under "Development Tools" (located on the left), click "API Connections".
3. Ensure each connection has been authorized.


## Steps to follow 
Before deploying the playbook you will need to add the credentials for both Open squat API https://rapidapi.com/atenreiro/api/opensquat1/)and also the MDTI API credentials (https://techcommunity.microsoft.com/t5/microsoft-defender-threat/what-s-new-apis-in-microsoft-graph/ba-p/3780350)
![image](https://user-images.githubusercontent.com/67633117/231843530-5e0b6f15-95ac-4fb5-8829-204ca6110bb4.png)

Click on the Deploy button and it will prompt you for the details
![image](https://user-images.githubusercontent.com/67633117/236240536-183b70e9-3909-4d49-91fa-a17f48d21c4b.png)

The playbook should be ready to Run and should send results to your selected email on basis 
![image](https://user-images.githubusercontent.com/67633117/236242629-28d2cebc-2562-4d9a-987c-3431099aa6af.png)



