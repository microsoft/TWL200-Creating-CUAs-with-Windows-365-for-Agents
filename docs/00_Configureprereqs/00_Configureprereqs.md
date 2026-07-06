---
title: 'Exercise 00: Configure prerequisites'
layout: default
nav_order: 2
has_children: true
---

# Exercise 00: Configure prerequisites
This exercise covers common configuration tasks. Before you create a cloud PC pool in Exercise 01, your tenant must meet the following requirements.

Depending on your tenant configuration, you may not need to complete every task in this exercise. Review the requirements and complete only the tasks needed for your environment.

- **Region**: Use United States regions for all Azure and Power Platform resources. Additional regions will be added as computer-use agents become generally available.

- **Azure subscription**: You must have an Azure subscription where you are assigned the Owner or Contributor role.

- **Power Platform environment**: Create a managed **Production Power Platform** environment in the United States region with Dataverse enabled.

- **Power Platform billing plan**: Create a billing plan in Power Platform admin center to associate your Azure subscription with the environment and enable metering.

- **Tenant authoring permissions**: Configure tenant authoring permissions. Without this configuration, pay-as-you-go behavior may be inconsistent. Agents may be created successfully, but cloud PC pools may fail.


Estimated time to complete this exercise: **50 minutes** 

## Learning resources
- [Automate web and desktop apps with computer use](https://learn.microsoft.com/en-us/microsoft-copilot-studio/computer-use)
- [Use Cloud PC pool for computer use runs](https://learn.microsoft.com/en-us/microsoft-copilot-studio/use-cloud-pc-pool)
- [Set up pay-as-you-go](https://learn.microsoft.com/en-us/power-platform/admin/pay-as-you-go-set-up?tabs=new)
- [Set up billing for Windows 365 agents](https://learn.microsoft.com/en-us/windows-365/agents/billing-w365a)


