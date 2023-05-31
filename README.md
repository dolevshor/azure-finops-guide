![FinOps-Logo-2](https://user-images.githubusercontent.com/69309933/211255358-23582f52-90cf-4eff-a34a-759b7a57f40a.jpg)


# The Azure FinOps Guide

**This guide centralizes Azure FinOps information and tools to enabling a better understanding and optimization of cloud costs.**

The main purposes of this guide is to do more with less by:
- Identifying cost-saving opportunities
- Optimizing cloud efficiency
- Gaining a better understanding and control of cloud costs

> The community is encouraged to contribute to this guide. If you have any suggestions for changes, additions, or removals to the content, please don't hesitate to submit a **pull request** or open a **issue**.

## Table of Contents

- [Tools](#tools)
- [Ways to optimize](#ways-to-optimize)
- [Learning](#learning)
  - [Learning Paths](#learning-paths)
  - [Learning Modules](#learning-modules)
- [Content](#content)
  - [General](#general)
  - [Calculators](#calculators)
  - [Cost Management](#cost-management)
  - [Advisor](#advisor)
  - [Azure Reservations](#azure-reservations)
  - [Savings Plans](#savings-plans)
  - [Azure Hybrid Benefit](#azure-hybrid-benefit)
  - [Virtual Machines](#virtual-machines)
  - [Virtual Machine Scale Sets](#virtual-machine-scale-sets)
  - [App Service](#app-service)
  - [AKS](#aks)
  - [Azure Stack HCI](#azure-stack-hci)
  - [Storage](#storage)
  - [Azure Monitor](#azure-monitor)
  - [Microsoft Sentinel](#microsoft-sentinel)
  - [Azure Virtual Desktop](#azure-virtual-desktop)
  - [Data](#data)
    - [Azure Synapse](#azure-synapse)
    - [Azure SQL Database](#azure-sql-database)
    - [SQL Managed Instance](#sql-managed-instance)
    - [Azure Database for MySQL](#azure-database-for-mysql)
    - [Azure Database for PostgreSQL](#azure-database-for-postgresql)
    - [Azure Cosmos DB](#azure-cosmos-db)
    - [Stream Analytics](#stream-analytics)

## Tools
The table below contains a collection of native tools that are related to FinOps on Azure.

| Tool Name                             | Description    |
| :-----------------------              | :----------------------- |
| [Azure Pricing Calculator][Tools-1]   | Allows you to mix and match different combinations of Azure services to see an estimate of the costs. |
| [Azure Cost Management][Tools-2]      | A suite of tools that help organizations to monitor, allocate, and optimize the cost of their Microsoft Cloud workloads. |
| [Azure Advisor][Tools-3]              | Analyses configurations and usage telemetry and offers personalized, actionable recommendations to help optimize resources for reliability, security, operational excellence, performance, and cost. |
| [TCO Calculator][Tools-4]             | TCO = Total Cost of Ownership <br /> Estimate the cost savings you can realize by migrating your workloads to Azure. |
| [Azure Hybrid Benefit Savings Calculator][Tools-5] | Estimates the price, savings, and eligible instances you can use in Azure based on your current Software Assurance licenses. (Windows VMs, SQL Server VMs, SQL Managed Instance, and SQL Database)  |

[//]: <> (Tools links)
[Tools-1]: https://azure.microsoft.com/en-us/pricing/calculator
[Tools-2]: https://azure.microsoft.com/en-us/products/cost-management/
[Tools-3]: https://azure.microsoft.com/en-au/products/advisor/
[Tools-4]: https://azure.microsoft.com/en-us/pricing/tco/calculator/
[Tools-5]: https://azure.microsoft.com/en-us/pricing/hybrid-benefit/#calculator

## Ways to optimize
This table contains a list of techniques to optimize and reduce your cloud environment's total cost of ownership.

| Topic                                        | Description |
| :-----------------------                     | :----------------------- |
| [Cut out waste][HowToOpt-1]                  | A [Workbook][WorkbookLink] to identify resources that are no longer being used. |
| [Azure Advisor][HowToOpt-2]                  | Analyses configurations and usage telemetry and offers personalized, actionable recommendations to help optimize resources for reliability, security, operational excellence, performance, and cost. |
| [Spot VMs][HowToOpt-3]                       | Buy unused compute capacity at significant cost savings. |
| [Saving Plans][HowToOpt-4]                   | Committing an hourly spend for Azure compute resources for a one-year or three-year plan. |
| [Azure Reservations][HowToOpt-5]             | Help you save money by committing to one-year or three-year plans for multiple products. |
| [Azure Hybrid Benefit][HowToOpt-6]           | 	Reduce the costs of running your workloads in the cloud using your on-premises Software Assurance-enabled Windows Server and SQL Server licenses on Azure. (Licensing benefit) |
| [On-Demand Capacity Reservation][HowToOpt-7] | Enables you to reserve Compute capacity in an Azure region or an Availability Zone for any duration of time without any commitment. |
| [Azure Reserved Capacity][HowToOpt-8]        | Save on Azure database services by pre-committing to fully-managed services. |
| [Software Plans][HowToOpt-9]                 | Reservation discount for deployed VMs with SUSE and RedHat software. |
| [Dev/Test pricing][HowToOpt-10]              | Significantly reduce the costs of ongoing dev/test workloads with discounted rates on Azure services. |

[//]: <> (How to optimize links)
[HowToOpt-1]: https://techcommunity.microsoft.com/t5/fasttrack-for-azure/azure-orphan-resources/ba-p/3492198
[HowToOpt-2]: https://azure.microsoft.com/en-au/products/advisor/
[HowToOpt-3]: https://learn.microsoft.com/en-us/azure/virtual-machines/spot-vms
[HowToOpt-4]: https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/savings-plan-compute-overview
[HowToOpt-5]: https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/save-compute-costs-reservations
[HowToOpt-6]: https://azure.microsoft.com/en-us/pricing/hybrid-benefit/
[HowToOpt-7]: https://learn.microsoft.com/en-us/azure/virtual-machines/capacity-reservation-overview
[HowToOpt-8]: https://azure.microsoft.com/en-gb/pricing/reserved-capacity/
[HowToOpt-9]: https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/understand-suse-reservation-charges
[HowToOpt-10]: https://azure.microsoft.com/en-gb/pricing/dev-test

[WorkbookLink]: https://github.com/dolevshor/azure-orphan-resources

## Learning
List of learning path references related to FinOps on Azure:

### Learning Paths

| Path Name                                  | Description              |
| :-----------------------                     | :----------------------- |
| [Control Azure spending and manage bills with Microsoft Cost Management + Billing][Learning-P-1] | Learn how to monitor and control your Azure spending and optimize the use of Azure resources. |

[//]: <> (Learning-Paths links)
[Learning-P-1]: https://learn.microsoft.com/en-us/training/paths/control-spending-manage-bills/

### Learning Modules

| Module Name                                  | Description              |
| :-----------------------                     | :----------------------- |
| [Microsoft Azure Well-Architected Framework – Cost Optimization][Learning-M-1] | Learn how to use the cost optimization pillar of the Microsoft Azure Well-Architected Framework to design a cloud-based architecture that is efficient, eliminates waste, and gives you full visibility into where your money is spent on cloud resources. |
| [Plan and manage your Azure costs][Learning-M-2] | Learn about the factors that influence cost and tools you can use to help estimate and manage your cloud spending. |
| [Introduction to analyzing costs and creating budgets with Microsoft Cost Management][Learning-M-3] | Learn how to use cost analysis to understand how your costs accrue each month. Use this understanding to create an Azure budget to monitor and alert you on your costs. |
| [Save money with Azure Reserved Instances][Learning-M-4] | Save money by taking advantage of Azure reservations. Analyze and decide what to purchase and then learn how to purchase. Understand the benefits provided through compute purchases and optimize against any underuse. Perform basic reporting on your reservations. |
| [Optimize Azure costs with data analysis in PowerBI][Learning-M-5] | Use Power BI to understand where your money is being spent in Azure so you can help your organization to optimize its costs. Identify key cost drivers, trends, and anomalies in your subscriptions and resource groups over time. Understand and manage hybrid benefits usage within your organization. Understand and optimize your reserved instance coverage to maximize your savings. Create custom dashboards to address your organization's more complex scenarios and analysis needs. |
| [Configure and manage costs as a Microsoft partner by using Microsoft Cost Management][Learning-M-6] | Reconcile your bill and analyze costs across your customers and resources using Microsoft Cost Management as a partner. Determine which of your resources receive discounted pricing. Manage costs through budgets to stay within defined spending limits. Enable your customers to use Microsoft Cost Management with pay-as-you-go rates. |

[//]: <> (Learning-Modules links)
[Learning-M-1]: https://learn.microsoft.com/en-us/training/modules/azure-well-architected-cost-optimization/
[Learning-M-2]: https://learn.microsoft.com/en-us/training/modules/plan-manage-azure-costs/
[Learning-M-3]: https://learn.microsoft.com/en-us/training/modules/analyze-costs-create-budgets-azure-cost-management/
[Learning-M-4]: https://learn.microsoft.com/en-us/training/modules/save-money-with-azure-reserved-instances/
[Learning-M-5]: https://learn.microsoft.com/en-us/training/modules/optimize-costs-data-analysis-powerbi/
[Learning-M-6]: https://learn.microsoft.com/en-us/training/modules/manage-costs-partner-cost-management/



## Content
This content summary brings together a wealth of information and resources on the discipline of FinOps in the cloud.

It covers a wide range of topics, domains, products, and resources collected from different channels like:

- Microsoft Tech Community (Blog Posts)
- Microsoft Azure (Official Docs)
- Microsoft Learn
- Microsoft Ignite
- Azure Friday
- YouTube
- GitHub

Whether you are new to FinOps or are an experienced professional, this summary is an invaluable resource for staying up-to-date with the latest developments and trends in the field.

[//]: <> (Authors list)
[John-Savill-1]: https://www.youtube.com/@NTFAQGuy
[Dolev-Shor-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1417490
[Dolev-Shor-2]: https://github.com/dolevshor
[Sam-Bell-1]: https://github.com/ms-sambell
[Michael-Flanakin-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/422097
[Halaa-Menasy-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/129267
[Sarah-Lean-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/347158
[Thomas-Maurer-1]: https://www.youtube.com/@Thomas_Maurer
[Shane-Baldacchino-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1176308
[Mayunk-Jain-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/114887
[Radhika-Bollineni-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1232070
[Paolo-Salvatori-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/988334
[Chee-Keong-Tan-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1563534
[Orestis-Meikopoulos-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/878885
[Bruno-Gabrielli-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/219011
[Innocent-Wafula-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/94294
[Kam-VedBrat-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/218481
[Kam-VedBrat-2]: https://ignite.microsoft.com/en-US/speakers/e99d048b-98ad-435a-b4e7-5f570cbbfd87
[Kate-Werner-1]: https://ignite.microsoft.com/en-US/speakers/f62d65cc-ba85-4ac6-886f-e21d07fb9183
[Luca-Ferrari-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1301810
[Uros-Milanovic-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/496888
[Bartłomiej-Graczyk-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/966827
[Julio-Calderón-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/288064
[Anasheh-Boisvert-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1395198
[Brandon-Wilson-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/140892
[Helder-Pinto-1]: https://github.com/helderpinto
[Helder-Pinto-2]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/453722
[Chris-Bowman-1]: https://github.com/chris-bowman
[Pranab-Paul-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1216949
[Arthur-Clares-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/703269
[Arthur-Clares-2]: https://github.com/arthurclares
[Michiel-van-Oudheusden-1]: https://github.com/mivano
[Ryan-Lowell-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1598778
[Ryan-Lowell-2]: https://github.com/rlowellfl
[Kaysie-Yu-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1222039
[Nir-Mashkowski-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1200080
[Saira-Shaik-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1017038
[Saira-Shaik-2]: https://github.com/sairashaik6677

### General

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Managing, reporting, and reducing your costs in Azure][General-1] | Scott Hanselman <br /> Barry Luijbregts | Dec 2022                 | Azure Friday             |
| [Azure Cost Optimization Deep Dive][General-2]                     | [John Savill][John-Savill-1]            | May 2020                 | YouTube                  |
| [Factors That Affect Costs][General-3]                             | [John Savill][John-Savill-1]            | Jan 2022                 | YouTube                  |
| [Factors to Reduce Cost][General-4]                                | [John Savill][John-Savill-1]            | Jan 2022                 | YouTube                  |
| [Azure Orphaned Resources][General-5]                              | [Dolev Shor][Dolev-Shor-1]              | Jun 2022                 | Microsoft Tech Community |
| [Azure Orphaned Resources Workbook][General-6]                     | [Dolev Shor][Dolev-Shor-2]              | Jun 2022                 | GitHub                   |
| [Azure FinOps Workbook][General-7]                                 | [Sam Bell][Sam-Bell-1]                  | Jan 2023                 | GitHub                   |
| [Azure Optimization Engine][General-8]                             | [Hélder Pinto][Helder-Pinto-1]          | Feb 2021                 | GitHub                   |


[General-1]: https://learn.microsoft.com/en-us/shows/azure-friday/managing-reporting-and-reducing-your-costs-in-azure
[General-2]: https://www.youtube.com/watch?v=RjuTQvGm1zQ
[General-3]: https://www.youtube.com/watch?v=fMShW_RGcxY
[General-4]: https://www.youtube.com/watch?v=B5yiKE2DLH8
[General-5]: https://techcommunity.microsoft.com/t5/fasttrack-for-azure/azure-orphan-resources/ba-p/3492198
[General-6]: https://github.com/dolevshor/azure-orphan-resources
[General-7]: https://github.com/ms-sambell/azure-finops-workbook
[General-8]: https://github.com/helderpinto/AzureOptimizationEngine

### Calculators

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Master the Azure Pricing Calculator][Calculator-1]                | [John Savill][John-Savill-1]            | Jun 2021               | YouTube                  |
| [Functionality and Usage of Pricing and TCO Calculators][Calculator-2] | [John Savill][John-Savill-1]        | Jan 2022               | YouTube                  |

[//]: <> (Calculators links)
[Calculator-1]: https://www.youtube.com/watch?v=rMKmbZ1SYQg
[Calculator-2]: https://www.youtube.com/watch?v=pE-bf8i5blU

### Cost Management

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Describe cost management in Azure][CostMgmt-1]                    | Microsoft                               |                          | Microsoft Learn          |
| [Azure Cost Management Overview][CostMgmt-2]                       | [Michael Flanakin][Michael-Flanakin-1]  | Aug 2022                 | Microsoft Tech Community |
| [Azure Cost Management for ISVs][CostMgmt-3]                       | [Halaa Menasy][Halaa-Menasy-1]          | Mar 2022                 | Microsoft Tech Community |
| [Azure Unblogged – Azure Cost Management][CostMgmt-4]              | [Sarah Lean][Sarah-Lean-1]              | Mar 2022                 | Microsoft Tech Community |
| [Functionality and Usage of Azure Cost Management][CostMgmt-5]     | [John Savill][John-Savill-1]            | Jan 2022                 | YouTube                  |
| [Create visuals and reports with the Azure Cost Management connector in Power BI Desktop][CostMgmt-6] | Microsoft | Aug 2022            |  Microsoft Learn \| Docs |
| [Azure Cost Management Power BI Report][CostMgmt-7]                | [Chris Bowman][Chris-Bowman-1]          | Feb 2023                 |  GitHub                  |
| [Project Bose: Calculate Azure Cost of an Enterprise by cost centers, divisions, projects][CostMgmt-8] | [Pranab Paul][Pranab-Paul-1] | Feb 2023 |  Microsoft Tech Community |
| [CLI tool to perform cost analysis on your Azure subscription][CostMgmt-9] | [Michiel van Oudheusden][Michiel-van-Oudheusden-1] | Apr 2023 |  GitHub               |


[//]: <> (Cost Management links)
[CostMgmt-1]: https://learn.microsoft.com/en-us/training/modules/describe-cost-management-azure/
[CostMgmt-2]: https://techcommunity.microsoft.com/t5/video-hub/azure-cost-management-overview/ba-p/2642242
[CostMgmt-3]: https://techcommunity.microsoft.com/t5/fasttrack-for-azure/azure-cost-management-for-isvs/ba-p/3255000
[CostMgmt-4]: https://techcommunity.microsoft.com/t5/itops-talk-blog/azure-unblogged-azure-cost-management/ba-p/2149786
[CostMgmt-5]: https://www.youtube.com/watch?v=FoBjC9CAF08
[CostMgmt-6]: https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-connect-azure-cost-management
[CostMgmt-7]: https://github.com/chris-bowman/Azure-Cost-Reporting
[CostMgmt-8]: https://techcommunity.microsoft.com/t5/azure-architecture-blog/codename-project-bose-calculate-azure-cost-of-an-enterprise-by/ba-p/3741295
[CostMgmt-9]: https://github.com/mivano/azure-cost-cli

### Advisor

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Intro to Azure Advisor][Advisor-1]                                | 	Microsoft                              |                          | Microsoft Learn          |
| [Get Started with Azure Advisor][Advisor-2]                        | 	Microsoft                              |                          | Microsoft Learn          |
| [Functionality and Usage of Azure Advisor][Advisor-3]              | [John Savill][John-Savill-1]            | Jan 2022                 | YouTube                  |
| [Optimize your Azure environment with Azure Advisor][Advisor-4]    | [Thomas Maurer][Thomas-Maurer-1]        | Apr 2021                 | YouTube                  |

[//]: <> (Advisor links)
[Advisor-1]: https://learn.microsoft.com/en-us/training/modules/intro-to-azure-advisor/
[Advisor-2]: https://learn.microsoft.com/en-us/training/modules/get-started-azure-advisor/
[Advisor-3]: https://www.youtube.com/watch?v=nqH4NboyEl0
[Advisor-4]: https://www.youtube.com/watch?v=ZZXYtxkwpQo


### Azure Reservations

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Azure Reservations (Reserved Instances) Deep Dive][Reservations-1]| [John Savill][John-Savill-1]            | Dec 2021                 | YouTube                  |
| [Reserved Instance and Capacity Reservations][Reservations-2]      | [John Savill][John-Savill-1]            | May 2022                 | YouTube                  |
| [Understanding Azure Reservations vs Savings Plans][Reservations-3]| [Brandon Wilson][Brandon-Wilson-1]      | Dec 2022                 | Microsoft Tech Community |
| [Azure Savings Dashboard][Reservations-4]                          | [Saira Shaik][Saira-Shaik-1]            | May 2023                 | Microsoft Tech Community |
| [Azure Savings Dashboard Tool][Reservations-5]                     | [Saira Shaik][Saira-Shaik-2]            | May 2023                 | GitHub                   |

[//]: <> (Reservations links)
[Reservations-1]: https://www.youtube.com/watch?v=vpTDXenagcM
[Reservations-2]: https://www.youtube.com/watch?v=43wX15ypp9Y
[Reservations-3]: https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/quick-reference-understanding-azure-reservations-vs-savings/ba-p/3689070
[Reservations-4]: https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/azure-savings-dashboard/ba-p/3816131
[Reservations-5]: https://github.com/sairashaik6677/azuresavingsdashboard

List of services that supported reservations:
![image](https://user-images.githubusercontent.com/69309933/210773383-feb62978-433a-40fe-b425-744c832348ae.png)

### Savings Plans

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Purchase Azure savings plan for compute][Saving-Plans-1]          | Microsoft                               |                          | Microsoft Learn          |
| [Understanding Azure Savings Plan for Compute][Saving-Plans-2]     | [John Savill][John-Savill-1]            | Oct 2022                 | YouTube                  |
| [Understanding Azure Reservations vs Savings Plans][Saving-Plans-3]| [Brandon Wilson][Brandon-Wilson-1]      | Dec 2022                 | Microsoft Tech Community |
| [View savings plan utilization][Saving-Plans-4]                    | Microsoft                               | Nov 2022                 | Microsoft Learn          |
| [View savings plan cost and usage][Saving-Plans-5]                 | Microsoft                               | Mar 2023                 | Microsoft Learn          |
| [View savings plan transactions][Saving-Plans-6]                   | Microsoft                               | Nov 2022                 | Microsoft Learn          |
| [Charge back savings plan costs][Saving-Plans-7]                   | Microsoft                               | Feb 2023                 | Microsoft Learn          |
| [Calculaye EA Cost savings][Saving-Plans-8]                        | Microsoft                               | Mar 2023                 | Microsoft Learn          |
| [Azure Savings Dashboard][Saving-Plans-9]                          | [Saira Shaik][Saira-Shaik-1]            | May 2023                 | Microsoft Tech Community |
| [Azure Savings Dashboard Tool][Saving-Plans-10]                    | [Saira Shaik][Saira-Shaik-2]            | May 2023                 | GitHub                   |


[//]: <> (Savings Plans links)
[Saving-Plans-1]: https://learn.microsoft.com/en-us/training/modules/azure-savings-plan-for-compute/
[Saving-Plans-2]: https://www.youtube.com/watch?v=lBnKBV2r6lI&t
[Saving-Plans-3]: https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/quick-reference-understanding-azure-reservations-vs-savings/ba-p/3689070
[Saving-Plans-4]: https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/view-utilization
[Saving-Plans-5]: https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/utilization-cost-reports
[Saving-Plans-6]: https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/view-transactions
[Saving-Plans-7]: https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/charge-back-costs
[Saving-Plans-8]: https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/calculate-ea-reservations-savings
[Saving-Plans-9]: https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/azure-savings-dashboard/ba-p/3816131
[Saving-Plans-10]: https://github.com/sairashaik6677/azuresavingsdashboard

### Azure Hybrid Benefit

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Azure Hybrid Benefit for Windows Server][AHUB-1]                  | Microsoft                               | Nov 2022                 | Microsoft Azure          |
| [Azure Hybrid Benefit for Linux Server][AHUB-2]                    | Microsoft                               | Aug 2022                 | Microsoft Azure          |
| [Azure Hybrid Benefit for SQL Virtual Machines][AHUB-3]            | Microsoft                               | Aug 2022                 | Microsoft Azure          |
| [Azure Hybrid Benefit for Azure SQL & Azure SQL Managed Instance][AHUB-4] | Microsoft                        | Aug 2022                 | Microsoft Azure          |
| [Azure Hybrid Benefit for Azure Kubernetes Service (AKS)][AHUB-5]  | Microsoft                               | Jul 2022                 | Microsoft Learn \| Docs  |
| [Azure Hybrid Benefit for Azure Stack HCI][AHUB-6]                 | Microsoft                               | Jul 2022                 | Microsoft Azure          |
| [Managing and Optimizing Your Azure Hybrid Benefit Usage][AHUB-7]  | [Arthur Clares][Arthur-Clares-1]        | Mar 2023                 | Microsoft Tech Community |
| [Azure Hybrid Benefit Workbook][AHUB-8]                            | [Arthur Clares][Arthur-Clares-2]        | Apr 2023                 | GitHub                   |
| [Tracking Azure Hybrid Benefit using Azure Workbooks][AHUB-9]      | [Ryan Lowell][Ryan-Lowell-1]            | Apr 2023                 | Microsoft Tech Community |
| [Azure Hybrid Benefit Tracking Dashboard][AHUB-10]                 | [Ryan Lowell][Ryan-Lowell-2]            | Apr 2023                 | GitHub                   |

[//]: <> (Azure Hybrid Benefit links)
[AHUB-1]: https://learn.microsoft.com/en-us/windows-server/get-started/azure-hybrid-benefit
[AHUB-2]: https://learn.microsoft.com/en-us/azure/virtual-machines/linux/azure-hybrid-benefit-linux
[AHUB-3]: https://learn.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/licensing-model-azure-hybrid-benefit-ahb-change
[AHUB-4]: https://learn.microsoft.com/en-us/azure/azure-sql/azure-hybrid-benefit
[AHUB-5]: https://learn.microsoft.com/en-us/azure/aks/hybrid/azure-hybrid-benefit
[AHUB-6]: https://learn.microsoft.com/en-us/azure-stack/hci/concepts/azure-hybrid-benefit-hci
[AHUB-7]: https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/managing-and-optimizing-your-azure-hybrid-benefit-usage-with/ba-p/3783541
[AHUB-8]: https://github.com/arthurclares/AzureHybridBenefitWorkbook
[AHUB-9]: https://techcommunity.microsoft.com/t5/healthcare-and-life-sciences/tracking-azure-hybrid-benefit-using-azure-workbooks/ba-p/3798857
[AHUB-10]: https://github.com/rlowellfl/azure_hybrid_benefit_workbook


### Virtual Machines

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Microsoft Azure Spot Virtual Machines overview][VMs-1]            | Rajeesh Ramachandran                    | Mar 2021                 | YouTube                  |
| [Azure Spot VM Deep Dive][VMs-2]                                   | [John Savill][John-Savill-1]            | Nov 2021                 | YouTube                  |
| [Understanding Windows Server IaaS Virtual Machine cost management][VMs-3] | Microsoft                       |                          | Microsoft Learn          |
| [Start/Stop VMs][VMs-4]                                            | Microsoft                               | Nov 2022               | Microsoft Learn | Docs   |
| [Part 2: Infra Cost Optimisation In The Cloud – Practical Design Steps For Architects and Developers][VMs-5] | [Shane Baldacchino][Shane-Baldacchino-1]| Aug 2022 | Microsoft Tech Community |

[//]: <> (Virtual Machines links)
[VMs-1]: https://www.youtube.com/watch?v=UfQgR-nLfno
[VMs-2]: https://www.youtube.com/watch?v=LWA4SCALYCY
[VMs-3]: https://learn.microsoft.com/en-us/training/modules/understand-windows-server-iaas-vm-cost-management/
[VMs-4]: https://learn.microsoft.com/en-us/azure/azure-functions/start-stop-vms/overview
[VMs-5]: https://techcommunity.microsoft.com/t5/azure-architecture-blog/part-2-infra-cost-optimisation-in-the-cloud-practical-design/ba-p/3602797


Additional topics that related to Virtual Machines:
- [Azure Reservations](#azure-reservations)
- [Azure Savings Plans](#savings-plans)
- [Azure Hybrid Benefit](#azure-hybrid-benefit) (Windows VM, Linux VM, SQL VM)

### Virtual Machine Scale Sets 

| Topic                                                               | Author                                  | Published                | Channel                  |
| :-----------------------                                            | :-----------------------                | :----------------------- | :----------------------- |
| [Spot Priority Mix for high availability and cost savings][VMSSs-1] | Microsoft                               |  Mar 2023                | Microsoft Learn          |

[//]: <> (Virtual Machines Scale Sets links)
[VMSSs-1]: https://learn.microsoft.com/en-us/azure/virtual-machine-scale-sets/spot-priority-mix

### App Service

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Plan and manage costs for Azure App Service][App-Service-1]       | Microsoft                               | Mar 2023                 | Microsoft Learn \| Docs  |
| [Estimate your cost savings by migrating to App Service Environment v3][App-Service-2] | Jordan Selig \| Microsoft | Mar 2023 | Azure App Service \| Team Blog  |
| [Azure App Service announces more ways to save on compute costs][App-Service-3] | [Mayunk Jain][Mayunk-Jain-1] | Nov 2022               | Microsoft Tech Community |
| [A lowered cost and more performant WordPress on Azure AppService][App-Service-4] | [Radhika Bollineni][Radhika-Bollineni-1] | Oct 2022 | Microsoft Tech Community |
| [Save up to 54% vs. on-premises and up to 35% vs. AWS by migrating your ASP.NET applications to Azure][App-Service-5] | [Mayunk Jain][Mayunk-Jain-1] | Sep 2022 | Microsoft Tech Community |
| [Celebrating 10 years of Azure App Services free tier][App-Service-6] | [Nir Mashkowski][Nir-Mashkowski-1]    | Sep 2022                | Microsoft Tech Community |
| [New Azure App Service plans fuel greater choice and savings][App-Service-7] | Naga Surendran \| Microsoft | Apr 2023 | Microsoft Azure Blog |
| [Forrester study finds 228 percent ROI when modernizing applications on Azure PaaS][App-Service-8] | Ashmi Chokshi \| Microsoft | Dec 2022 | Microsoft Azure Blog |

[//]: <> (App Service links)
[App-Service-1]: https://learn.microsoft.com/en-us/azure/app-service/overview-manage-costs
[App-Service-2]: https://azure.github.io/AppService/2023/03/02/App-service-environment-v3-pricing
[App-Service-3]: https://techcommunity.microsoft.com/t5/apps-on-azure-blog/azure-app-service-announces-more-ways-to-save-on-compute-costs/ba-p/3664398
[App-Service-4]: https://techcommunity.microsoft.com/t5/apps-on-azure-blog/a-lowered-cost-and-more-performant-wordpress-on-azure-appservice/ba-p/3647860
[App-Service-5]: https://techcommunity.microsoft.com/t5/apps-on-azure-blog/save-up-to-54-vs-on-premises-and-up-to-35-vs-aws-by-migrating/ba-p/3596627
[App-Service-6]: https://techcommunity.microsoft.com/t5/apps-on-azure-blog/celebrating-10-years-of-azure-app-service-s-free-tier/ba-p/3621148
[App-Service-7]: https://azure.microsoft.com/en-us/blog/new-azure-app-service-plans-fuel-greater-choice-and-savings/
[App-Service-8]: https://azure.microsoft.com/en-us/blog/forrester-study-finds-228-percent-roi-when-modernizing-applications-on-azure-paas/


### AKS

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Optimize compute costs on Azure Kubernetes Service (AKS)][AKS-1]  | Microsoft                               |                          | Microsoft Learn | Training |
| [How to reduce the total cost of ownership (TCO) of your Azure Kubernetes Service (AKS) cluster][AKS-2] | [Paolo Salvatori][Paolo-Salvatori-1] | 	Jan 2023 | Microsoft Tech Community |
| [Azure Kubernetes Service (AKS) – Cost Optimization Techniques][AKS-3] | [Chee Keong Tan][Chee-Keong-Tan-1]  | Oct 2022                | Microsoft Tech Community  |
| [AKS Container Insights logging level and associated costs][AKS-4] | [Orestis Meikopoulos][Orestis-Meikopoulos-1] | Nov 2022           | Microsoft Tech Community  |
| [Azure Hybrid Benefit for Azure Kubernetes Service (AKS)][AKS-5]   | Microsoft                               | Jul 2022                | Microsoft Learn | Docs    |
| [Leverage OpenCost on Azure Kubernetes Service to understand and monitor your infrastructure spend][AKS-6] | [Kaysie Yu][Kaysie-Yu-1] | Apr 2023 | Microsoft Tech Community  |



[//]: <> (AKS links)
[AKS-1]: https://learn.microsoft.com/en-us/training/modules/aks-optimize-compute-costs
[AKS-2]: https://techcommunity.microsoft.com/t5/fasttrack-for-azure/how-to-reduce-the-total-cost-of-ownership-tco-of-your-azure/ba-p/3706895
[AKS-3]: https://techcommunity.microsoft.com/t5/apps-on-azure-blog/azure-kubernetes-service-aks-cost-optimization-techniques/ba-p/3652908
[AKS-4]: https://techcommunity.microsoft.com/t5/fasttrack-for-azure/aks-container-insights-logging-level-and-associated-costs/ba-p/3684224
[AKS-5]: https://learn.microsoft.com/en-us/azure/aks/hybrid/azure-hybrid-benefit
[AKS-6]: https://techcommunity.microsoft.com/t5/apps-on-azure-blog/leverage-opencost-on-azure-kubernetes-service-to-understand-and/ba-p/3796813

### Azure Stack HCI

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Azure Hybrid Benefit for Azure Stack HCI][HCI-1]                  | Microsoft                               |  Jul 2022                | Microsoft Azure          |

[//]: <> (Azure Stack HCI links)
[HCI-1]: https://learn.microsoft.com/en-us/azure-stack/hci/concepts/azure-hybrid-benefit-hci


### Storage

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Optimizing your storage costs with Azure Blob Storage][STG-1]     | Scott Hanselman <br /> Klaas Langhout   | Apr 2021                 | Microsoft Friday         |
| [Optimize your cost with Azure Blob Storage][STG-2]                | Microsoft                               |                          | Microsoft Learn          |
| [Optimize performance and costs by using Azure Disk Storage][STG-3]| Microsoft                               |                          |  Microsoft Learn         |
| [Optimize storage performance and costs using Blog storage tiers][STG-4]| Microsoft                          |                          | Microsoft Learn          |
| [Plan and manage costs for Azure Blob Storage][STG-5]              | Microsoft                               | Dec 2022                 | Microsoft Azure          |
| [Optimize costs by automatically managing the data lifecycle][STG-6]| Microsoft                              | Dec 2022                 | Microsoft Azure          |
| [Optimize costs for Blob storage with reserved capacity][STG-7]    | Microsoft                               | Jul 2022                 | Microsoft Azure          |
| [Estimate the cost of archiving data][STG-8]                       | Microsoft                               | Dec 2022                 | Microsoft Azure          |
| [Part 2: Infra Cost Optimization In The Cloud – Practical Design Steps For Architects and Developers][STG-9] | [Shane Baldacchino][Shane-Baldacchino-1]| Aug 2022  | Microsoft Tech Community |
| [Storage Accounts and cost optimization][STG-10]                   | Microsoft                               | Jan 2022                 | Microsoft Learn | Docs   |
| [Calculate the size of a blob container with PowerShell][STG-11]   | Microsoft                               | Apr 2022                 | Microsoft Learn | Docs   |
| [Calculate the total billing size of a blob container][STG-11]     | Microsoft                               | Mar 2023                 | Microsoft Learn | Docs   |

[//]: <> (Storage links)
[STG-1]: https://learn.microsoft.com/en-us/shows/azure-friday/optimizing-your-storage-costs-with-azure-blob-storage
[STG-2]: https://learn.microsoft.com/en-us/training/modules/optimize-your-cost-azure-blob-storage
[STG-3]: https://learn.microsoft.com/en-us/training/modules/optimize-performance-and-costs-using-azure-disk-storage
[STG-4]: https://learn.microsoft.com/en-us/training/modules/optimize-archive-costs-blob-storage
[STG-5]: https://learn.microsoft.com/en-us/azure/storage/common/storage-plan-manage-costs
[STG-6]: https://learn.microsoft.com/en-us/azure/storage/blobs/lifecycle-management-overview
[STG-7]: https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-reserved-capacity
[STG-8]: https://learn.microsoft.com/en-us/azure/storage/blobs/archive-cost-estimation
[STG-9]: https://techcommunity.microsoft.com/t5/azure-architecture-blog/part-2-infra-cost-optimisation-in-the-cloud-practical-design/ba-p/3602797
[STG-10]: https://learn.microsoft.com/en-us/azure/well-architected/services/storage/storage-accounts/cost-optimization
[STG-11]: https://learn.microsoft.com/en-us/azure/storage/scripts/storage-blobs-container-calculate-size-powershell
[STG-12]: https://learn.microsoft.com/en-us/azure/storage/scripts/storage-blobs-container-calculate-billing-size-powershell


### Azure Monitor

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Cost optimization and Azure Monitor][Monitor-1]                   | Microsoft                               | Dec 2022                 | Microsoft Azure          |
| [Analyze usage in Log Analytics workspace][Monitor-2]              | Microsoft                               | Mar 2023                 | Microsoft Azure          |
| [Set a table's log data plan to Basic or Analytics][Monitor-3]     | Microsoft                               | Jan 2023                 | Microsoft Azure          |
| [Calculating Chargeback to Split Monitoring Costs Across Projects][Monitor-4]| [Bruno Gabrielli][Bruno-Gabrielli-1]|  Nov 2022          | Microsoft Tech Community |
| [How to Allocate Azure Monitor Logs Ingestion Costs by Resource Tag][Monitor-5]| [Helder Pinto][Helder-Pinto-2]|  May 2023              | Microsoft Tech Community |

[//]: <> (Azure Monitor links)
[Monitor-1]: https://learn.microsoft.com/en-us/azure/azure-monitor/best-practices-cost
[Monitor-2]: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/analyze-usage
[Monitor-3]: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/basic-logs-configure
[Monitor-4]: https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/azure-monitor-calculating-chargeback-to-split-monitoring-costs/ba-p/3671760
[Monitor-5]: https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/how-to-allocate-azure-monitor-logs-ingestion-costs-by-resource/ba-p/3813322


### Microsoft Sentinel

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Ingestion Cost Spike Detection Playbook][Sentinel-1]              | [Innocent Wafula][Innocent-Wafula-1]    | Aug 2021               | Microsoft Tech Community |
| [Ingestion Cost Alert Playbook][Sentinel-2]                        | [Innocent Wafula][Innocent-Wafula-1]    | Dec 2022               | Microsoft Tech Community |
| [Cost Management in Azure Sentinel][Sentinel-3]                    | Javier Soriano <br /> Jeremy Tan <br /> Innocent Wafula| Jun 2021| YouTube                  |

[//]: <> (Azure Sentinel links)
[Sentinel-1]: https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/ingestion-cost-spike-detection-playbook/ba-p/2591301
[Sentinel-2]: https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/ingestion-cost-alert-playbook/ba-p/2006003
[Sentinel-3]: https://www.youtube.com/watch?v=jZjBK2oRCsM


### Azure Virtual Desktop

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Optimize Azure Virtual Desktop][AVD-1]                            | Microsoft                               |                          | Microsoft Learn          |
| [New ways to optimize flexibility, improve security, and reduce costs with Azure Virtual Desktop][AVD-2]| [Kam VedBrat][Kam-VedBrat-1] | Oct 2022| Microsoft Tech Community |
| [New ways to optimize flexibility, improve security, and reduce costs with Azure Virtual Desktop][AVD-3]| [Kam VedBrat][Kam-VedBrat-2] <br /> [Kate Werner][Kate-Werner-1]| Oct 2022 | Microsoft Ignite|

[//]: <> (Azure Virtual Desktop links)
[AVD-1]: https://learn.microsoft.com/en-us/training/modules/m365-optimize-wvd/
[AVD-2]: https://techcommunity.microsoft.com/t5/azure-virtual-desktop-blog/new-ways-to-optimize-flexibility-improve-security-and-reduce/ba-p/3650895
[AVD-3]: https://ignite.microsoft.com/en-US/sessions/e016948a-1646-420e-9597-fae2b6d3ce29


### Data

#### Azure Synapse

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Synapse Serverless SQL Pool - Performance and cost optimization with partitioning][Synapse-1] | [Luca Ferrari][Luca-Ferrari-1] | Nov 2022 | Microsoft Learn     |
| [Cost management for serverless SQL pool in Azure Synapse Analytics][Synapse-2]| Microsoft                   | Apr 2022               | Microsoft Learn \| Docs  |
| [Configure cost control for serverless SQL pool in Synapse Studio][Synapse-3]|   Microsoft                   | Apr 2022               | Microsoft Learn \| Docs  |

[//]: <> (Azure Synapse links)
[Synapse-1]: https://techcommunity.microsoft.com/t5/fasttrack-for-azure/synapse-serverless-sql-pool-performance-and-cost-optimization/ba-p/3673286
[Synapse-2]: https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/data-processed
[Synapse-3]: https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/data-processed#cost-control


#### Azure SQL Database

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Plan and manage costs for Azure SQL Database][SQL-1]              | Microsoft                               | Sep 2022                 | Microsoft Learn \| Docs  |
| [Azure SQL Database and cost optimization][SQL-2]                  | Microsoft                               | Jun 2022                 | Microsoft Learn \| Docs  |

[//]: <> (Azure SQL Database links)
[SQL-1]: https://learn.microsoft.com/en-us/azure/azure-sql/database/cost-management
[SQL-2]: https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/data-processed


#### SQL Managed Instance

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Optimize cost of SQL Managed Instances with new stop-start capability][SQLMI-1]| [Uros Milanovic][Uros-Milanovic-1] | Nov 2022       | Microsoft Tech Community |
| [Optimize your Azure SQL Managed Instance cost with Microsoft Azure Well-Architected Framework][SQLMI-2]| [Bartłomiej Graczyk][Bartłomiej-Graczyk-1]|Mar 2021| Microsoft Tech Community|

[//]: <> (Azure SQL Managed Instance links)
[SQLMI-1]: https://techcommunity.microsoft.com/t5/azure-sql-blog/optimize-cost-of-sql-managed-instances-with-new-stop-start/ba-p/3677508 
[SQLMI-2]: https://techcommunity.microsoft.com/t5/azure-sql-blog/optimize-your-azure-sql-managed-instance-cost-with-microsoft/ba-p/2235216 


#### Azure Database for MySQL

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Azure Database for MySQL and cost optimization][MySQL-1]          | Microsoft                               | Dec 2022               | Microsoft Learn \| Docs  |
| [How to auto-scale an Azure Database for MySQL/PostgreSQL instance with Azure run books and Python][MySQL-2]| [Julio Calderón][Julio-Calderón-1]| Mar 2019| Microsoft Tech Community|

[//]: <> (Azure SQL Database links)
[MySQL-1]: https://learn.microsoft.com/en-us/azure/architecture/framework/services/data/azure-db-mysql/cost-optimization
[MySQL-2]: https://techcommunity.microsoft.com/t5/azure-database-support-blog/how-to-auto-scale-an-azure-database-for-mysql-postgresql/ba-p/369177


#### Azure Database for PostgreSQL

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Azure Database for MySQL and cost optimization][PostgeSQL-1]      | Microsoft                               | Dec 2022               | Microsoft Learn \| Docs  |
| [How to auto-scale an Azure Database for MySQL/PostgreSQL instance with Azure run books and Python][PostgeSQL-2]| [Julio Calderón][Julio-Calderón-1]| Mar 2019| Microsoft Tech Community|

[//]: <> (Azure Database for PostgreSQL links)
[PostgeSQL-1]: https://learn.microsoft.com/en-us/azure/architecture/framework/services/data/azure-db-postgresql/cost-optimization
[PostgeSQL-2]: https://techcommunity.microsoft.com/t5/azure-database-support-blog/how-to-auto-scale-an-azure-database-for-mysql-postgresql/ba-p/369177


#### Azure Cosmos DB

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Plan and manage costs for Azure Cosmos DB][Cosmos-1]              | Microsoft                               | Oct 2022               | Microsoft Learn \| Docs  |

[//]: <> (Azure Cosmos DB links)
[Cosmos-1]: https://learn.microsoft.com/en-us/azure/cosmos-db/plan-manage-costs


#### Stream Analytics

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Optimize your Stream Analytics Job and Reduce Costs with Autoscale][Stream-1] | [Anasheh Boisvert][Anasheh-Boisvert-1]| May 2022     | Microsoft Tech Community |

[//]: <> (Azure Stream Analytics links)
[Stream-1]: https://techcommunity.microsoft.com/t5/analytics-on-azure-blog/optimize-your-stream-analytics-job-and-reduce-costs-with/ba-p/3423493
