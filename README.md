# Threat Hunting - Microsoft Foundry
Initiating threat hunting efforts with Microsoft Foundry. 
# Target Architecture
<img width="1081" height="402" alt="AzureFoundryTH drawio (1)" src="https://github.com/user-attachments/assets/3d4aecaf-75e0-4008-acc3-9b4f7b0e2159" />

# Objective 
To streamlime the process of Threat Hunting by integrating Artifical Intelligence into the workflow

## Benefits: 
- Natural Language Threat Hunting
- Faster Investigation and Correlation
- Automated KQL Generation and Optimization
- Guided Incident Response
- Easily understand the in's and out's of the threat

# Solution 
- Foundry uses Microsoft Sentinel MCP (Microsoft Sentinel Data Exploration)
- Data Lake is not present, App Registration is created and given Sentinel Platform Delegated API Access.
<img width="1052" height="188" alt="Sentinel" src="https://github.com/user-attachments/assets/da8f8e51-a877-44c6-aa5b-0e6350a4c8e5" />

- Foundry with Sentinel MCP will be able to access Sentinel without needing a data lake present. 
<img width="747" height="774" alt="image" src="https://github.com/user-attachments/assets/70524722-8773-4272-a885-c893d349eccb" />

# Final (unofficial) look
<img width="1691" height="845" alt="image" src="https://github.com/user-attachments/assets/f5aa1014-7a2e-43d0-9b08-41e80be816aa" />

- "Instructions" are basically what is how the AI is supposed to act and what they're supposed to do.

# Key Considerations 
- I'm currently using Azure for Students, so some of the access are not available such as the Sentinel Platform Delegated API Access.
- Full final view is not achievable with this subscription.
- No data lake involved

<img width="715" height="751" alt="image" src="https://github.com/user-attachments/assets/6fd09740-429c-4d89-84d8-26d418493660" />









