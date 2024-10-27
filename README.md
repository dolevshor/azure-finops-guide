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
- [Books](#books)
- [Content](#content)
  - [General](#general)
  - [Calculators](#calculators)
  - [Cost Management](#cost-management)
  - [Advisor](#advisor)
  - [Azure Reservations](#azure-reservations)
  - [Azure Savings Plan](#azure-savings-plan)
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
  - [Azure Logic Apps](#azure-logic-apps)
  - [Azure Functions](#azure-functions)
  - [Networking](#networking) 
    - [Azure Front Door](#azure-front-door)
    - [Azure Application Gateway](#azure-application-gateway)
  - [Data](#data)
    - [Azure Synapse](#azure-synapse)
    - [Azure SQL Database](#azure-sql-database)
    - [Azure SQL Managed Instance](#azure-sql-managed-instance)
    - [Azure Database for MySQL](#azure-database-for-mysql)
    - [Azure Database for PostgreSQL](#azure-database-for-postgresql)
    - [Azure Cosmos DB](#azure-cosmos-db)
    - [Azure Stream Analytics](#azure-stream-analytics)
    - [Azure Databricks](#azure-databricks)
  - [Azure AI Services](#azure-ai-services)
    - [Azure OpenAI Service](#azure-openai-service)
  - [FOCUS™](#focus)


## Tools
The table below contains a collection of native tools that are related to FinOps on Azure.

| Tool Name                             | Description    |
| :-----------------------              | :----------------------- |
| [Azure Pricing Calculator][Tools-1]   | Allows you to mix and match different combinations of Azure services to see an estimate of the costs. |
| [Azure Cost Management][Tools-2]      | A suite of tools that help organizations to monitor, allocate, and optimize the cost of their Microsoft Cloud workloads. |
| [Azure Advisor][Tools-3]              | Analyses configurations and usage telemetry and offers personalized, actionable recommendations to help optimize resources for reliability, security, operational excellence, performance, and cost. |
| [TCO Calculator][Tools-4]             | TCO = Total Cost of Ownership <br /> Estimate the cost savings you can realize by migrating your workloads to Azure. |
| [Azure Hybrid Benefit Savings Calculator][Tools-5] | Estimates the price, savings, and eligible instances you can use in Azure based on your current Software Assurance licenses. (Windows VMs, SQL Server VMs, SQL Managed Instance, and SQL Database)  |
| [FinOps toolkit][Tools-6]             | Starter kits, scripts, and advanced solutions to accelerate your FinOps journey in the Microsoft Cloud. |

[//]: <> (Tools links)
[Tools-1]: https://azure.microsoft.com/en-us/pricing/calculator
[Tools-2]: https://azure.microsoft.com/en-us/products/cost-management/
[Tools-3]: https://azure.microsoft.com/en-au/products/advisor/
[Tools-4]: https://azure.microsoft.com/en-us/pricing/tco/calculator/
[Tools-5]: https://azure.microsoft.com/en-us/pricing/hybrid-benefit/#calculator
[Tools-6]: https://microsoft.github.io/finops-toolkit/

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
| [Introduction to analyzing costs and creating budgets with Microsoft Cost Management][Learning-M-2] | Learn how to use cost analysis to understand how your costs accrue each month. Use this understanding to create an Azure budget to monitor and alert you on your costs. |
| [Save money with Azure Reserved Instances][Learning-M-3] | Save money by taking advantage of Azure reservations. Analyze and decide what to purchase and then learn how to purchase. Understand the benefits provided through compute purchases and optimize against any underuse. Perform basic reporting on your reservations. |
| [Optimize Azure costs with data analysis in PowerBI][Learning-M-4] | Use Power BI to understand where your money is being spent in Azure so you can help your organization to optimize its costs. Identify key cost drivers, trends, and anomalies in your subscriptions and resource groups over time. Understand and manage hybrid benefits usage within your organization. Understand and optimize your reserved instance coverage to maximize your savings. Create custom dashboards to address your organization's more complex scenarios and analysis needs. |
| [Configure and manage costs as a Microsoft partner by using Microsoft Cost Management][Learning-M-5] | Reconcile your bill and analyze costs across your customers and resources using Microsoft Cost Management as a partner. Determine which of your resources receive discounted pricing. Manage costs through budgets to stay within defined spending limits. Enable your customers to use Microsoft Cost Management with pay-as-you-go rates. |
| [Purchase Azure savings plan for compute][Learning-M-6] | Purchase Azure savings plan for compute. |

[//]: <> (Learning-Modules links)
[Learning-M-1]: https://learn.microsoft.com/en-us/training/modules/azure-well-architected-cost-optimization/
[Learning-M-2]: https://learn.microsoft.com/en-us/training/modules/analyze-costs-create-budgets-azure-cost-management/
[Learning-M-3]: https://learn.microsoft.com/en-us/training/modules/save-money-with-azure-reserved-instances/
[Learning-M-4]: https://learn.microsoft.com/en-us/training/modules/optimize-costs-data-analysis-powerbi/
[Learning-M-5]: https://learn.microsoft.com/en-us/training/modules/manage-costs-partner-cost-management/
[Learning-M-6]: https://learn.microsoft.com/en-us/training/modules/azure-savings-plan-for-compute/


## Books
List of books references related to FinOps on Azure:

| Book Name                                      | Description                                                                     | Author                    | Published                | Channel                  |
| :-----------------------                       | :-----------------------                                                        | :-----------------------  | :----------------------- | :----------------------- |
| [FinOps with Azure][Books-1]                   | Bringing FinOps to life through organizational and cultural alignment           | Microsoft                 | May 2022                 | Microsoft E-books        |
| [The Road to Azure Cost Governance][Books-2]   | Techniques to tame your monthly Azure bill with a continuous optimization journey for your apps | Paola E. Annis <br /> Giuliano Caglio | Nov 2022 | Microsoft E-books |
| [FinOps Handbook for Microsoft Azure][Books-3] | Empowering teams to optimize their Azure Cloud spend with FinOps best practices | Maulik Soni               | May 2023                 | O'Reilly                 |

[Books-1]: https://azure.microsoft.com/en-us/resources/finops-with-azure-bringing-finops-to-life-through-organizational-and-cultural-alignment
[Books-2]: https://azure.microsoft.com/en-us/resources/the-road-to-azure-cost-governance
[Books-3]: https://www.oreilly.com/library/view/finops-handbook-for/9781801810166



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
[Michael-Flanakin-2]: https://azure.microsoft.com/en-us/blog/author/michael-flanakin
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
[Jeremy-Tan-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/215052
[Shishir-Garde-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1873751
[Shikha-Sinha-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1566597
[Oren-Salzberg-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/733057
[Yoav-Dobrin-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1306386
[James-Croft-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/2097623
[Antonio-Ortoll-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1595602
[Olga-Molocenco-Ciureanu-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1103062
[Kyle-Ikeda-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/849111
[Antonio-Ortoll-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1595602
[Gregor-Wohlfarter-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1053914
[Obinna-Nwokolo-1]: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/1563823


### General

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [FinOps Blog][General-1]                                            | Microsoft                              |                          | Microsoft Tech Community |
| [Managing, reporting, and reducing your costs in Azure][General-2] | Scott Hanselman <br /> Barry Luijbregts | Dec 2022                 | Azure Friday             |
| [Azure Cost Optimization Deep Dive][General-3]                     | [John Savill][John-Savill-1]            | May 2020                 | YouTube                  |
| [Factors That Affect Costs][General-4]                             | [John Savill][John-Savill-1]            | Jan 2022                 | YouTube                  |
| [Factors to Reduce Cost][General-5]                                | [John Savill][John-Savill-1]            | Jan 2022                 | YouTube                  |
| [Communicating a cost savings initiative the right way and what NOT to do][General-6] | [John Savill][John-Savill-1] | Dec 2023         | YouTube                  |
| [Azure Orphaned Resources][General-7]                              | [Dolev Shor][Dolev-Shor-1]              | Jun 2022                 | Microsoft Tech Community |
| [Azure Orphaned Resources Workbook][General-8]                     | [Dolev Shor][Dolev-Shor-2]              | Jun 2022                 | GitHub                   |
| [Azure FinOps Workbook][General-9]                                 | [Sam Bell][Sam-Bell-1]                  | Jan 2023                 | GitHub                   |
| [Azure Optimization Engine][General-10]                            | [Hélder Pinto][Helder-Pinto-1]          | Feb 2021                 | GitHub                   |
| [Cost allocation is imperative for cloud resource optimization][General-11] | [Antonio Ortoll][Antonio-Ortoll-1] | Apr 2024             | Microsoft Tech Community |
| [Identify your savings potential in Azure][General-12]             | [Gregor Wohlfarter][Gregor-Wohlfarter-1] | Aug 2024                | Microsoft Tech Community |
| [FinOps and Azure! Understanding what FinOps is and why we care][General-13] | [John Savill][John-Savill-1]  | May 2024                 | YouTube                  |
| [Interconnected guidance for an optimized cloud journey][General-14] | [Antonio Ortoll][Antonio-Ortoll-1]    | Jul 2024                 | Microsoft Tech Community |
| [Combine FinOps best practices and Microsoft tools to streamline and optimize your workloads][General-15] | [Antonio Ortoll][Antonio-Ortoll-1] | Jul 2024 | Microsoft Tech Community |

[//]: <> (General links)
[General-1]: https://techcommunity.microsoft.com/t5/finops-blog/bg-p/FinOpsBlog
[General-2]: https://learn.microsoft.com/en-us/shows/azure-friday/managing-reporting-and-reducing-your-costs-in-azure
[General-3]: https://www.youtube.com/watch?v=RjuTQvGm1zQ
[General-4]: https://www.youtube.com/watch?v=fMShW_RGcxY
[General-5]: https://www.youtube.com/watch?v=B5yiKE2DLH8
[General-6]: https://www.youtube.com/watch?v=a1txqsKSafk
[General-7]: https://techcommunity.microsoft.com/t5/fasttrack-for-azure/azure-orphan-resources/ba-p/3492198
[General-8]: https://github.com/dolevshor/azure-orphan-resources
[General-9]: https://github.com/ms-sambell/azure-finops-workbook
[General-10]: https://github.com/helderpinto/AzureOptimizationEngine
[General-11]: https://techcommunity.microsoft.com/t5/finops-blog/cost-allocation-is-imperative-for-cloud-resource-optimization/ba-p/4114921
[General-12]: https://techcommunity.microsoft.com/t5/finops-blog/identify-your-savings-potential-in-azure/ba-p/4131194
[General-13]: https://www.youtube.com/watch?v=YHUptdFtozQ
[General-14]: https://techcommunity.microsoft.com/t5/finops-blog/interconnected-guidance-for-an-optimized-cloud-journey/ba-p/4006134
[General-15]: https://techcommunity.microsoft.com/t5/finops-blog/combine-finops-best-practices-and-microsoft-tools-to-streamline/ba-p/4093343

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
| [Take control of your cloud spend with Microsoft Cost Management][CostMgmt-10] | [Antonio Ortoll][Antonio-Ortoll-1] | Jan 2024          | Microsoft Tech Community |
| [Leverage anomaly management processes with Microsoft Cost Management][CostMgmt-11] | [Antonio Ortoll][Antonio-Ortoll-1] | Feb 2024     | Microsoft Tech Community |
| [Use budget management and forecasting to bring your FinOps practice into the era of AI][CostMgmt-12] | [Antonio Ortoll][Antonio-Ortoll-1] | Jun 2024 | Microsoft Tech Community |
| [Improve visibility into workload-related spend using Copilot in Microsoft Cost Management][CostMgmt-13] | [Antonio Ortoll][Antonio-Ortoll-1] | Nov 2023 | Microsoft Tech Community |
| [How to budget your Azure cloud spend with Microsoft Cost Management][CostMgmt-14] | [Gregor Wohlfarter][Gregor-Wohlfarter-1] | Jun 2024 | Microsoft Tech Community |
| [Creating Azure Budgets][CostMgmt-15]                              | [John Savill][John-Savill-1]            | Oct 2024                 | YouTube                  |

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
[CostMgmt-10]: https://techcommunity.microsoft.com/t5/azure-governance-and-management/take-control-of-your-cloud-spend-with-microsoft-cost-management/ba-p/4024213
[CostMgmt-11]: https://techcommunity.microsoft.com/t5/finops-blog/leverage-anomaly-management-processes-with-microsoft-cost/ba-p/4072380
[CostMgmt-12]: https://techcommunity.microsoft.com/t5/finops-blog/use-budget-management-and-forecasting-to-bring-your-finops/ba-p/4173661
[CostMgmt-13]: https://techcommunity.microsoft.com/t5/finops-blog/improve-visibility-into-workload-related-spend-using-copilot-in/ba-p/3986503
[CostMgmt-14]: https://techcommunity.microsoft.com/t5/finops-blog/how-to-budget-your-azure-cloud-spend-with-microsoft-cost/ba-p/4153963
[CostMgmt-15]: https://www.youtube.com/watch?v=MRWR_9JMsF4

### Advisor

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Intro to Azure Advisor][Advisor-1]                                | 	Microsoft                              |                          | Microsoft Learn          |
| [Get Started with Azure Advisor][Advisor-2]                        | 	Microsoft                              |                          | Microsoft Learn          |
| [Azure Advisor Cost recommendations][Advisor-3]                    | 	Microsoft                              | Oct 2023                 | Microsoft Learn \| Docs  |
| [Functionality and Usage of Azure Advisor][Advisor-4]              | [John Savill][John-Savill-1]            | Jan 2022                 | YouTube                  |
| [Optimize your Azure environment with Azure Advisor][Advisor-5]    | [Thomas Maurer][Thomas-Maurer-1]        | Apr 2021                 | YouTube                  |
| [Optimize your Cloud investment with new Azure Advisor Workbooks][Advisor-6] | [Antonio Ortoll][Antonio-Ortoll-1] | Oct 2023            | Microsoft Tech Community |
| [3 reasons to optimize your workloads with Azure Advisor][Advisor-7] | [Antonio Ortoll][Antonio-Ortoll-1]    | Nov 2022                 | Microsoft Tech Community |

[//]: <> (Advisor links)
[Advisor-1]: https://learn.microsoft.com/en-us/training/modules/intro-to-azure-advisor/
[Advisor-2]: https://learn.microsoft.com/en-us/training/modules/get-started-azure-advisor/
[Advisor-3]: https://learn.microsoft.com/en-us/azure/advisor/advisor-reference-cost-recommendations
[Advisor-4]: https://www.youtube.com/watch?v=nqH4NboyEl0
[Advisor-5]: https://www.youtube.com/watch?v=ZZXYtxkwpQo
[Advisor-6]: https://techcommunity.microsoft.com/t5/azure-governance-and-management/optimize-your-cloud-investment-with-new-azure-advisor-workbooks/ba-p/3950911
[Advisor-7]: https://techcommunity.microsoft.com/t5/azure-architecture-blog/3-reasons-to-optimize-your-workloads-with-azure-advisor/ba-p/3674044


### Azure Reservations

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Azure Reservations (Reserved Instances) Deep Dive][Reservations-1]| [John Savill][John-Savill-1]            | Dec 2021                 | YouTube                  |
| [Reserved Instance and Capacity Reservations][Reservations-2]      | [John Savill][John-Savill-1]            | May 2022                 | YouTube                  |
| [Understanding Azure Reservations vs Savings Plans][Reservations-3]| [Brandon Wilson][Brandon-Wilson-1]      | Dec 2022                 | Microsoft Tech Community |
| [Azure Savings Dashboard][Reservations-4]                          | [Saira Shaik][Saira-Shaik-1]            | May 2023                 | Microsoft Tech Community |
| [Azure Savings Dashboard Tool][Reservations-5]                     | [Saira Shaik][Saira-Shaik-2]            | May 2023                 | GitHub                   |
| [Reservation utilization alerts][Reservations-6]                   | Microsoft                               | May 2023                 | Microsoft Learn \| Docs  |
| [Get Azure Reservations and Savings Plans Insights with the Azure Optimization Engine][Reservations-7] | [Helder Pinto][Helder-Pinto-2] | Apr 2024 | Microsoft Tech Community |
| [How to optimize your Azure compute spend with savings plan and reserved instances][Reservations-8] | [Kyle Ikeda][Kyle-Ikeda-1] | Mar 2024 | Microsoft Tech Community |
| [How to choose the right reserved instance in Azure][Reservations-9]| [Gregor Wohlfarter][Gregor-Wohlfarter-1] <br /> [Helder Pinto][Helder-Pinto-2] | May 2024 | Microsoft Tech Community |
| [What's the difference between Azure savings plans for compute and Azure reservations?][Reservations-10]| [Gregor Wohlfarter][Gregor-Wohlfarter-1] <br /> [Obinna Nwokolo][Obinna-Nwokolo-1] | Jul 2024 | Microsoft Tech Community |

[//]: <> (Reservations links)
[Reservations-1]: https://www.youtube.com/watch?v=vpTDXenagcM
[Reservations-2]: https://www.youtube.com/watch?v=43wX15ypp9Y
[Reservations-3]: https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/quick-reference-understanding-azure-reservations-vs-savings/ba-p/3689070
[Reservations-4]: https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/azure-savings-dashboard/ba-p/3816131
[Reservations-5]: https://github.com/sairashaik6677/azuresavingsdashboard
[Reservations-6]: https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/reservation-utilization-alerts
[Reservations-7]: https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/get-azure-reservations-and-savings-plans-insights-with-the-azure/ba-p/4100750
[Reservations-8]: https://techcommunity.microsoft.com/t5/azure-compute-blog/how-to-optimize-your-azure-compute-spend-with-savings-plan-and/ba-p/4076115
[Reservations-9]: https://techcommunity.microsoft.com/t5/finops-blog/how-to-choose-the-right-reserved-instance-in-azure/ba-p/4124218
[Reservations-10]: https://techcommunity.microsoft.com/t5/finops-blog/what-s-the-difference-between-azure-savings-plans-for-compute/ba-p/4147506

List of services that supported reservations:

![image](https://github.com/dolevshor/azure-finops-guide/assets/69309933/f3b3c59f-4ca3-4bd2-a710-359914ed50f3)


| Service Name                                                       | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [App Service][BuyReservation-1]                                    | Microsoft                               | Mar 2023                 | Microsoft Azure          |
| [App Service - JBoss EA Integrated Support][BuyReservation-2]      | Microsoft                               | Nov 2023                 | Microsoft Azure          |
| [Azure Backup][BuyReservation-3]                                   | Microsoft                               | Feb 2023                 | Microsoft Azure          |
| [Azure Cache for Redis][BuyReservation-4]                          | Microsoft                               | Aug 2022                 | Microsoft Azure          |
| [Azure Data Factory][BuyReservation-5]                             | Microsoft                               | Jul 2023                 | Microsoft Azure          |
| [Azure Database for MariaDB][BuyReservation-6]                     | Microsoft                               | Sep 2023                 | Microsoft Azure          |
| [Azure Database for MySQL][BuyReservation-7]                       | Microsoft                               | Dec 2023                 | Microsoft Azure          |
| [Azure Database for PostgreSQL][BuyReservation-8]                  | Microsoft                               | Jan 2024                 | Microsoft Azure          |
| [Azure Blob storage][BuyReservation-9]                             | Microsoft                               | Mar 2023                 | Microsoft Azure          |
| [Azure Files][BuyReservation-10]                                   | Microsoft                               | Mar 2023                 | Microsoft Azure          |
| [Azure VMware Solution][BuyReservation-11]                         | Microsoft                               | Dec 2023                 | Microsoft Azure          |
| [Azure Cosmos DB][BuyReservation-12]                               | Microsoft                               | Nov 2022                 | Microsoft Azure          |
| [Azure SQL Edge][BuyReservation-13]                                | Microsoft                               | Nov 2023                 | Microsoft Azure          |
| [Azure Databricks][BuyReservation-14]                              | Microsoft                               | Nov 2023                 | Microsoft Azure          |
| [Azure Data Explorer][BuyReservation-15]                           | Microsoft                               | Mar 2022                 | Microsoft Azure          |
| [Azure Dedicated Host][BuyReservation-16]                          | Microsoft                               | Jun 2023                 | Microsoft Azure          |
| [Azure Managed Disks][BuyReservation-17]                           | Microsoft                               | Jan 2023                 | Microsoft Azure          |
| [Microsoft Fabric][BuyReservation-18]                              | Microsoft                               | Nov 2023                 | Microsoft Azure          |
| [SAP HANA Large Instances][BuyReservation-19]                      | Microsoft                               | Mar 2023                 | Microsoft Azure          |
| [Software plans][BuyReservation-20]                                | Microsoft                               | Jun 2022                 | Microsoft Azure          |
| [SQL Database and SQL Managed Instance][BuyReservation-21]         | Microsoft                               | Sep 2023                 | Microsoft Azure          |
| [Azure Synapse Analytics (data warehousing only)][BuyReservation-22]| Microsoft                              | Nov 2023                 | Microsoft Azure          |
| [Synapse Analytics - Pre-Purchase Plan][BuyReservation-23]         | Microsoft                               | Mar 2023                 | Microsoft Azure          |
| [Virtual machines][BuyReservation-24]                              | Microsoft                               | Jan 2023                 | Microsoft Azure          |
| [Virtual machine software][BuyReservation-25]                      | Microsoft                               | Nov 2023                 | Microsoft Azure          |
| [Azure Red Hat OpenShift][BuyReservation-26]                       | Microsoft                               |                          | Microsoft Azure          |
| [Azure Arc-enabled SQL Managed Instance][BuyReservation-27]        | Microsoft                               | Aug 2022                 | Microsoft Azure          |


[//]: <> (Buy Reservations links)
[BuyReservation-1]: https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/prepay-app-service
[BuyReservation-2]: https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/prepay-jboss-eap-integrated-support-app-service
[BuyReservation-3]: https://learn.microsoft.com/en-us/azure/backup/backup-azure-reserved-pricing-optimize-cost
[BuyReservation-4]: https://learn.microsoft.com/en-us/azure/azure-cache-for-redis/cache-reserved-pricing
[BuyReservation-5]: https://learn.microsoft.com/en-us/azure/data-factory/data-flow-reserved-capacity-overview
[BuyReservation-6]: https://learn.microsoft.com/en-us/azure/mariadb/concept-reserved-pricing
[BuyReservation-7]: https://learn.microsoft.com/en-us/azure/mysql/flexible-server/concept-reserved-pricing
[BuyReservation-8]: https://learn.microsoft.com/en-us/azure/postgresql/flexible-server/concepts-reserved-pricing
[BuyReservation-9]: https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-reserved-capacity
[BuyReservation-10]: https://learn.microsoft.com/en-us/azure/storage/files/files-reserve-capacity
[BuyReservation-11]: https://learn.microsoft.com/en-us/azure/azure-vmware/reserved-instance
[BuyReservation-12]: https://learn.microsoft.com/en-us/azure/cosmos-db/reserved-capacity
[BuyReservation-13]: https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/prepay-sql-edge
[BuyReservation-14]: https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/prepay-databricks-reserved-capacity
[BuyReservation-15]: https://learn.microsoft.com/en-us/azure/data-explorer/pricing-reserved-capacity
[BuyReservation-16]: https://learn.microsoft.com/en-us/azure/virtual-machines/prepay-dedicated-hosts-reserved-instances
[BuyReservation-17]: https://learn.microsoft.com/en-us/azure/virtual-machines/disks-reserved-capacity
[BuyReservation-18]: https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/fabric-capacity
[BuyReservation-19]: https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/prepay-hana-large-instances-reserved-capacity
[BuyReservation-20]: https://learn.microsoft.com/en-us/azure/virtual-machines/linux/prepay-suse-software-charges
[BuyReservation-21]: https://learn.microsoft.com/en-us/azure/azure-sql/database/reserved-capacity-overview
[BuyReservation-22]: https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/prepay-sql-data-warehouse-charges
[BuyReservation-23]: https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/synapse-analytics-pre-purchase-plan
[BuyReservation-24]: https://learn.microsoft.com/en-us/azure/virtual-machines/prepay-reserved-vm-instances
[BuyReservation-25]: https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/buy-vm-software-reservation
[BuyReservation-26]: https://azure.microsoft.com/en-us/pricing/details/openshift
[BuyReservation-27]: https://learn.microsoft.com/en-us/azure/azure-arc/data/reserved-capacity-overview

### Azure Savings Plan

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Purchase Azure savings plan for compute][Savings-Plan-1]          | Microsoft                               |                          | Microsoft Learn          |
| [Understanding Azure Savings Plan for Compute][Savings-Plan-2]     | [John Savill][John-Savill-1]            | Oct 2022                 | YouTube                  |
| [Understanding Azure Reservations vs Savings Plans][Savings-Plan-3]| [Brandon Wilson][Brandon-Wilson-1]      | Dec 2022                 | Microsoft Tech Community |
| [View savings plan utilization][Savings-Plan-4]                    | Microsoft                               | Nov 2022                 | Microsoft Learn          |
| [View savings plan cost and usage][Savings-Plan-5]                 | Microsoft                               | Mar 2023                 | Microsoft Learn          |
| [View savings plan transactions][Savings-Plan-6]                   | Microsoft                               | Nov 2022                 | Microsoft Learn          |
| [Charge back savings plan costs][Savings-Plan-7]                   | Microsoft                               | Feb 2023                 | Microsoft Learn          |
| [Calculate EA Cost savings][Savings-Plan-8]                        | Microsoft                               | Mar 2023                 | Microsoft Learn          |
| [Azure Savings Dashboard][Savings-Plan-9]                          | [Saira Shaik][Saira-Shaik-1]            | May 2023                 | Microsoft Tech Community |
| [Azure Savings Dashboard Tool][Savings-Plan-10]                    | [Saira Shaik][Saira-Shaik-2]            | May 2023                 | GitHub                   |
| [Get Azure Reservations and Savings Plans Insights with the Azure Optimization Engine][Savings-Plan-11] | [Helder Pinto][Helder-Pinto-2] | Apr 2024 | Microsoft Tech Community |
| [How to optimize your Azure compute spend with savings plan and reserved instances][Savings-Plan-12] | [Kyle Ikeda][Kyle-Ikeda-1] | Mar 2024 | Microsoft Tech Community |
| [What's the difference between Azure savings plans for compute and Azure reservations?][Savings-Plan-13]| [Gregor Wohlfarter][Gregor-Wohlfarter-1] <br /> [Obinna Nwokolo][Obinna-Nwokolo-1] | Jul 2024 | Microsoft Tech Community |


[//]: <> (Savings Plan links)
[Savings-Plan-1]: https://learn.microsoft.com/en-us/training/modules/azure-savings-plan-for-compute/
[Savings-Plan-2]: https://www.youtube.com/watch?v=lBnKBV2r6lI&t
[Savings-Plan-3]: https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/quick-reference-understanding-azure-reservations-vs-savings/ba-p/3689070
[Savings-Plan-4]: https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/view-utilization
[Savings-Plan-5]: https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/utilization-cost-reports
[Savings-Plan-6]: https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/view-transactions
[Savings-Plan-7]: https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/charge-back-costs
[Savings-Plan-8]: https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/calculate-ea-reservations-savings
[Savings-Plan-9]: https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/azure-savings-dashboard/ba-p/3816131
[Savings-Plan-10]: https://github.com/sairashaik6677/azuresavingsdashboard
[Savings-Plan-11]: https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/get-azure-reservations-and-savings-plans-insights-with-the-azure/ba-p/4100750
[Savings-Plan-12]: https://techcommunity.microsoft.com/t5/azure-compute-blog/how-to-optimize-your-azure-compute-spend-with-savings-plan-and/ba-p/4076115
[Savings-Plan-13]: https://techcommunity.microsoft.com/t5/finops-blog/what-s-the-difference-between-azure-savings-plans-for-compute/ba-p/4147506

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
| [Optimize compute costs on Azure Kubernetes Service (AKS)][AKS-1]  | Microsoft                               |                          | Microsoft Learn \| Training |
| [Optimize costs in Azure Kubernetes Service (AKS)][AKS-2]          | Microsoft                               | Apr 2023                 | Microsoft Learn \| Docs |
| [Cost management for Kubernetes][AKS-3]                            | Microsoft                               | Jan 2023                 | Microsoft Learn \| Docs |
| [Cost governance with Kubecost][AKS-4]                             | Microsoft                               | Jun 2023                | Microsoft Learn \| Docs |
| [How to reduce the total cost of ownership (TCO) of your Azure Kubernetes Service (AKS) cluster][AKS-5] | [Paolo Salvatori][Paolo-Salvatori-1] | 	Jan 2023 | Microsoft Tech Community |
| [Azure Kubernetes Service (AKS) – Cost Optimization Techniques][AKS-6] | [Chee Keong Tan][Chee-Keong-Tan-1]  | Oct 2022                | Microsoft Tech Community  |
| [AKS Container Insights logging level and associated costs][AKS-7] | [Orestis Meikopoulos][Orestis-Meikopoulos-1] | Nov 2022           | Microsoft Tech Community  |
| [Azure Hybrid Benefit for Azure Kubernetes Service (AKS)][AKS-8]   | Microsoft                               | Jul 2022                | Microsoft Learn \| Docs    |
| [Leverage OpenCost on Azure Kubernetes Service to understand and monitor your infrastructure spend][AKS-9] | [Kaysie Yu][Kaysie-Yu-1] | Apr 2023 | Microsoft Tech Community  |
| [Container insights - Cluster Optimization Workbook][AKS-10]       | Microsoft                               | May 2023                | Microsoft Learn \| Docs    |
| [Understand monitoring costs for Container insights][AKS-11]       | Microsoft                               | May 2023                 | Microsoft Learn \| Docs |


[//]: <> (AKS links)
[AKS-1]: https://learn.microsoft.com/en-us/training/modules/aks-optimize-compute-costs
[AKS-2]: https://learn.microsoft.com/en-us/azure/aks/best-practices-cost
[AKS-3]: https://learn.microsoft.com/en-us/azure/architecture/aws-professional/eks-to-aks/cost-management
[AKS-4]: https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/aks/cost-governance-with-kubecost
[AKS-5]: https://techcommunity.microsoft.com/t5/fasttrack-for-azure/how-to-reduce-the-total-cost-of-ownership-tco-of-your-azure/ba-p/3706895
[AKS-6]: https://techcommunity.microsoft.com/t5/apps-on-azure-blog/azure-kubernetes-service-aks-cost-optimization-techniques/ba-p/3652908
[AKS-7]: https://techcommunity.microsoft.com/t5/fasttrack-for-azure/aks-container-insights-logging-level-and-associated-costs/ba-p/3684224
[AKS-8]: https://learn.microsoft.com/en-us/azure/aks/hybrid/azure-hybrid-benefit
[AKS-9]: https://techcommunity.microsoft.com/t5/apps-on-azure-blog/leverage-opencost-on-azure-kubernetes-service-to-understand-and/ba-p/3796813
[AKS-10]: https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-reports#cluster-optimization-workbook
[AKS-11]: https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-cost#estimating-costs-to-monitor-your-aks-cluster

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
| [Optimize performance and costs by using Azure Disk Storage][STG-3]| Microsoft                               |                          | Microsoft Learn          |
| [Optimize storage performance and costs using Blog storage tiers][STG-4]| Microsoft                          |                          | Microsoft Learn          |
| [Plan and manage costs for Azure Blob Storage][STG-5]              | Microsoft                               | Dec 2022                 | Microsoft Azure          |
| [Optimize costs by automatically managing the data lifecycle][STG-6]| Microsoft                              | Dec 2022                 | Microsoft Azure          |
| [Optimize costs for Blob storage with reserved capacity][STG-7]    | Microsoft                               | Apr 2023                 | Microsoft Azure          |
| [Estimate the cost of archiving data][STG-8]                       | Microsoft                               | Dec 2022                 | Microsoft Azure          |
| [Part 2: Infra Cost Optimization In The Cloud – Practical Design Steps For Architects and Developers][STG-9] | [Shane Baldacchino][Shane-Baldacchino-1]| Aug 2022  | Microsoft Tech Community |
| [Storage Accounts and cost optimization][STG-10]                   | Microsoft                               | Jan 2022                 | Microsoft Learn | Docs   |
| [Calculate the size of a blob container with PowerShell][STG-11]   | Microsoft                               | Apr 2022                 | Microsoft Learn | Docs   |
| [Calculate the total billing size of a blob container][STG-12]     | Microsoft                               | Mar 2023                 | Microsoft Learn | Docs   |
| [BlobInsight: Your Deep Dive into Smart Blob Lifecycle Management][STG-13]| [Yoav Dobrin][Yoav-Dobrin-1]     | Sep 2023                 | Microsoft Tech Community |

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
[STG-13]: https://techcommunity.microsoft.com/t5/fasttrack-for-azure/from-blobs-to-insights-your-guide-to-smart-storage-lifecycle/ba-p/3921021


### Azure Monitor

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Cost optimization and Azure Monitor][Monitor-1]                   | Microsoft                               | Dec 2022                 | Microsoft Azure          |
| [Analyze usage in Log Analytics workspace][Monitor-2]              | Microsoft                               | Mar 2023                 | Microsoft Azure          |
| [Azure Monitor Logs cost calculations and options][Monitor-3]      | Microsoft                               | Jun 2023                 | Microsoft Azure          |
| [Azure Monitor cost and usage][Monitor-4]                          | Microsoft                               | Apr 2023                 | Microsoft Azure          |
| [Set a table's log data plan to Basic or Analytics][Monitor-5]     | Microsoft                               | Jan 2023                 | Microsoft Azure          |
| [Calculating Chargeback to Split Monitoring Costs Across Projects][Monitor-6]| [Bruno Gabrielli][Bruno-Gabrielli-1]|  Nov 2022          | Microsoft Tech Community |
| [How to Allocate Azure Monitor Logs Ingestion Costs by Resource Tag][Monitor-7]| [Helder Pinto][Helder-Pinto-2]|  May 2023              | Microsoft Tech Community |
| [Azure Monitor cost optimization using Azure Advisor][Monitor-8]   | [Oren Salzberg][Oren-Salzberg-1]        |  Sep 2023                | Microsoft Tech Community |

[//]: <> (Azure Monitor links)
[Monitor-1]: https://learn.microsoft.com/en-us/azure/azure-monitor/best-practices-cost
[Monitor-2]: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/analyze-usage
[Monitor-3]: https://learn.microsoft.com/en-us/azure/azure-monitor/usage-estimated-costs
[Monitor-4]: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/cost-logs
[Monitor-5]: https://learn.microsoft.com/en-us/azure/azure-monitor/logs/basic-logs-configure
[Monitor-6]: https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/azure-monitor-calculating-chargeback-to-split-monitoring-costs/ba-p/3671760
[Monitor-7]: https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/how-to-allocate-azure-monitor-logs-ingestion-costs-by-resource/ba-p/3813322
[Monitor-8]: https://techcommunity.microsoft.com/t5/azure-observability-blog/azure-monitor-cost-optimization-using-azure-advisor/ba-p/3917488


### Microsoft Sentinel

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Manage and monitor costs for Microsoft Sentinel][Sentinel-1]      | Microsoft                               | Jul 2023                 | Microsoft Learn \| Docs  |
| [Reduce costs for Microsoft Sentinel][Sentinel-2]                  | Microsoft                               | Jul 2023                 | Microsoft Learn \| Docs  |
| [Ingestion Cost Spike Detection Playbook][Sentinel-3]              | [Innocent Wafula][Innocent-Wafula-1]    | Aug 2021                 | Microsoft Tech Community |
| [Ingestion Cost Alert Playbook][Sentinel-4]                        | [Innocent Wafula][Innocent-Wafula-1]    | Dec 2022                 | Microsoft Tech Community |
| [Cost Management in Azure Sentinel][Sentinel-5]                    | Javier Soriano <br /> Jeremy Tan <br /> Innocent Wafula| Jun 2021  | YouTube                  |
| [Introducing Microsoft Sentinel Optimization Workbook][Sentinel-6] | [Jeremy Tan][Jeremy-Tan-1]              | Aug 2023                 | Microsoft Tech Community |

[//]: <> (Azure Sentinel links)
[Sentinel-1]: https://learn.microsoft.com/en-us/azure/sentinel/billing-monitor-costs
[Sentinel-2]: https://learn.microsoft.com/en-us/azure/sentinel/billing-reduce-costs
[Sentinel-3]: https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/ingestion-cost-spike-detection-playbook/ba-p/2591301
[Sentinel-4]: https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/ingestion-cost-alert-playbook/ba-p/2006003
[Sentinel-5]: https://www.youtube.com/watch?v=jZjBK2oRCsM
[Sentinel-6]: https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/introducing-microsoft-sentinel-optimization-workbook/ba-p/3901489


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


### Azure Logic Apps

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Plan and manage costs for Azure Logic Apps][LogicApps-1]          | Microsoft                               | Sep 2022                 | Microsoft Learn \| Docs  |
| [Usage metering, billing, and pricing for Azure Logic Apps][LogicApps-2] | Microsoft                         | Apr 2023                 | Microsoft Learn \| Docs  |
| [Estimate storage costs for Standard logic app workflows in single-tenant Azure Logic Apps][LogicApps-3] | Microsoft | Aug 2022         | Microsoft Learn \| Docs  |


[//]: <> (Azure Logic Apps links)
[LogicApps-1]: https://learn.microsoft.com/en-us/azure/logic-apps/plan-manage-costs
[LogicApps-2]: https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-pricing
[LogicApps-3]: https://learn.microsoft.com/en-us/azure/logic-apps/estimate-storage-costs


### Azure Functions

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Estimating Consumption plan costs][Functions-1]                   | Microsoft                               | Feb 2023                 | Microsoft Learn \| Docs  |


[//]: <> (Azure Functions links)
[Functions-1]: https://learn.microsoft.com/en-us/azure/azure-functions/functions-consumption-costs


### Networking

#### Azure Front Door

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Understand Azure Front Door billing][FrontDoor-1]                 | Microsoft                               | Feb 2023                 | Microsoft Learn \| Docs  |
| [Compare pricing between Azure Front Door tiers][FrontDoor-2]      | Microsoft                               | Jun 2023                 | Microsoft Learn \| Docs  |

[//]: <> (Front Door links)
[FrontDoor-1]: https://learn.microsoft.com/en-us/azure/frontdoor/billing
[FrontDoor-2]: https://learn.microsoft.com/en-us/azure/frontdoor/understanding-pricing#cost-assessment

#### Azure Application Gateway

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Understanding Pricing for Azure Application Gateway and Web Application Firewall][AppGW-1] | Microsoft      | Jan 2023                 | Microsoft Learn \| Docs  |

[//]: <> (Azure Application Gateway links)
[AppGW-1]: https://learn.microsoft.com/en-us/azure/application-gateway/understanding-pricing


### Data

#### Azure Synapse

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Plan and manage costs for Azure Synapse Analytics][Synapse-1]     | Microsoft                               | Feb 2023               | Microsoft Learn \| Docs  |
| [Cost management for serverless SQL pool in Azure Synapse Analytics][Synapse-2]| Microsoft                   | Apr 2022               | Microsoft Learn \| Docs  |
| [Configure cost control for serverless SQL pool in Synapse Studio][Synapse-3]|   Microsoft                   | Apr 2022               | Microsoft Learn \| Docs  |
| [Synapse Serverless SQL Pool - Performance and cost optimization with partitioning][Synapse-4] | [Luca Ferrari][Luca-Ferrari-1] | Nov 2022 | Microsoft Learn     |

[//]: <> (Azure Synapse links)
[Synapse-1]: https://learn.microsoft.com/en-us/azure/synapse-analytics/plan-manage-costs
[Synapse-2]: https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/data-processed
[Synapse-3]: https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/data-processed#cost-control
[Synapse-4]: https://techcommunity.microsoft.com/t5/fasttrack-for-azure/synapse-serverless-sql-pool-performance-and-cost-optimization/ba-p/3673286


#### Azure SQL Database

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Plan and manage costs for Azure SQL Database][SQL-1]              | Microsoft                               | Sep 2022                 | Microsoft Learn \| Docs  |
| [Azure SQL Database and cost optimization][SQL-2]                  | Microsoft                               | Jun 2022                 | Microsoft Learn \| Docs  |
| [NEW FREE Azure SQL Database][SQL-3]                               | [John Savill][John-Savill-1]            | Oct 2024                 | YouTube                  |

[//]: <> (Azure SQL Database links)
[SQL-1]: https://learn.microsoft.com/en-us/azure/azure-sql/database/cost-management
[SQL-2]: https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/data-processed
[SQL-3]: https://www.youtube.com/watch?v=Xhks_sxZL7E


#### Azure SQL Managed Instance

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
| [Prepay for Azure Database for MySQL compute resources with reserved instances][MySQL-1] | Microsoft         | Sep 2022                 | Microsoft Learn \| Docs  |
| [How to auto-scale an Azure Database for MySQL/PostgreSQL instance with Azure run books and Python][MySQL-2]| [Julio Calderón][Julio-Calderón-1]| Mar 2019| Microsoft Tech Community|
| [Azure Database for MySQL and cost optimization][MySQL-3]          | Microsoft                               | Dec 2022               | Microsoft Learn \| Docs  |

[//]: <> (Azure Database for MySQL links)
[MySQL-1]: https://learn.microsoft.com/en-us/azure/mysql/single-server/concept-reserved-pricing
[MySQL-2]: https://techcommunity.microsoft.com/t5/azure-database-support-blog/how-to-auto-scale-an-azure-database-for-mysql-postgresql/ba-p/369177
[MySQL-3]: https://learn.microsoft.com/en-us/azure/architecture/framework/services/data/azure-db-mysql/cost-optimization


#### Azure Database for PostgreSQL

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [How to optimize costs in Azure Database for Postgres Flexible Server][PostgeSQL-1] | Microsoft              | Apr 2023                 | Microsoft Learn \| Docs  |
| [How to auto-scale an Azure Database for MySQL/PostgreSQL instance with Azure run books and Python][PostgeSQL-2]| [Julio Calderón][Julio-Calderón-1]| Mar 2019| Microsoft Tech Community|
| [Azure Database for PostgreSQL and cost optimization][PostgeSQL-3]      | Microsoft                               | May 2023               | Microsoft Learn \| Docs  |

[//]: <> (Azure Database for PostgreSQL links)
[PostgeSQL-1]: https://learn.microsoft.com/en-us/azure/postgresql/flexible-server/how-to-cost-optimization
[PostgeSQL-2]: https://techcommunity.microsoft.com/t5/azure-database-support-blog/how-to-auto-scale-an-azure-database-for-mysql-postgresql/ba-p/369177
[PostgeSQL-3]: https://learn.microsoft.com/en-us/azure/architecture/framework/services/data/azure-db-postgresql/cost-optimization


#### Azure Cosmos DB

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Plan and manage costs for Azure Cosmos DB][Cosmos-1]              | Microsoft                               | Oct 2022                 | Microsoft Learn \| Docs  |
| [Limit the total throughput provisioned on your Azure Cosmos DB account][Cosmos-2] | Microsoft               | Apr 2023                 | Microsoft Learn \| Docs  |
| [Optimize cost with reserved capacity in Azure Cosmos DB][Cosmos-3] | Microsoft                              | Mar 2024                 | Microsoft Learn \| Docs  |
| [Improve performance and optimize costs when upgrading to Azure Cosmos DB API for MongoDB 4.0+][Cosmos-4] | Microsoft | Jun 2022        | Microsoft Learn \| Docs  |
| [Optimize development and testing cost in Azure Cosmos DB][Cosmos-5] | Microsoft                             | Oct 2022                 | Microsoft Learn \| Docs  |
| [Azure Synapse Link for Azure Cosmos DB][Cosmos-6]                 | Microsoft                               | Feb 2023                 | Microsoft Learn \| Docs  |
| [Pricing model in Azure Cosmos DB][Cosmos-7]                       | Microsoft                               | Jan 2024                 | Microsoft Learn \| Docs  |
| [Total Cost of Ownership (TCO) with Azure Cosmos DB][Cosmos-8]     | Microsoft                               | Nov 2022                 | Microsoft Learn \| Docs  |
| [Understand your Azure Cosmos DB bill][Cosmos-9]                   | Microsoft                               | Oct 2022                 | Microsoft Learn \| Docs  |
| [Optimize provisioned throughput cost in Azure Cosmos DB][Cosmos-10] | Microsoft                             | Oct 2022                 | Microsoft Learn \| Docs  |
| [Optimize storage cost in Azure Cosmos DB][Cosmos-11]              | Microsoft                               | Oct 2022                 | Microsoft Learn \| Docs  |
| [Optimize multi-region cost in Azure Cosmos DB][Cosmos-12]         | Microsoft                               | Feb 2024                 | Microsoft Learn \| Docs  |
| [Optimize your Azure Cosmos DB application using rate limiting][Cosmos-13] | Microsoft                       | Oct 2022                 | Microsoft Learn \| Docs  |
| [Optimize request cost in Azure Cosmos DB][Cosmos-14]              | Microsoft                               | Apr 2023                 | Microsoft Learn \| Docs  |

[//]: <> (Azure Cosmos DB links)
[Cosmos-1]: https://learn.microsoft.com/azure/cosmos-db/plan-manage-costs
[Cosmos-2]: https://learn.microsoft.com/azure/cosmos-db/limit-total-account-throughput
[Cosmos-3]: https://learn.microsoft.com/azure/cosmos-db/reserved-capacity
[Cosmos-4]: https://learn.microsoft.com/azure/cosmos-db/mongodb/compression-cost-savings
[Cosmos-5]: https://learn.microsoft.com/azure/cosmos-db/optimize-dev-test
[Cosmos-6]: https://learn.microsoft.com/azure/cosmos-db/synapse-link
[Cosmos-7]: https://learn.microsoft.com/en-us/azure/cosmos-db/how-pricing-works
[Cosmos-8]: https://learn.microsoft.com/en-us/azure/cosmos-db/total-cost-ownership
[Cosmos-9]: https://learn.microsoft.com/en-us/azure/cosmos-db/understand-your-bill
[Cosmos-10]: https://learn.microsoft.com/en-us/azure/cosmos-db/optimize-cost-throughput
[Cosmos-11]: https://learn.microsoft.com/en-us/azure/cosmos-db/optimize-cost-storage
[Cosmos-12]: https://learn.microsoft.com/en-us/azure/cosmos-db/optimize-cost-regions
[Cosmos-13]: https://learn.microsoft.com/en-us/azure/cosmos-db/rate-limiting-requests
[Cosmos-14]: https://learn.microsoft.com/en-us/azure/cosmos-db/optimize-cost-reads-writes


#### Azure Stream Analytics

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Optimize your Stream Analytics Job and Reduce Costs with Autoscale][Stream-1] | [Anasheh Boisvert][Anasheh-Boisvert-1]| May 2022     | Microsoft Tech Community |

[//]: <> (Azure Stream Analytics links)
[Stream-1]: https://techcommunity.microsoft.com/t5/analytics-on-azure-blog/optimize-your-stream-analytics-job-and-reduce-costs-with/ba-p/3423493


#### Azure Databricks

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Cost optimization for the data lakehouse][Databricks-1]           | Microsoft                               | May 2023                 | Microsoft Learn \| Docs  |
| [Best practices for cost optimization][Databricks-2]               | Microsoft                               | Jun 2023                 | Microsoft Learn \| Docs  |

[//]: <> (Azure Databricks links)
[Databricks-1]: https://learn.microsoft.com/en-us/azure/databricks/lakehouse-architecture/cost-optimization
[Databricks-2]: https://learn.microsoft.com/en-us/azure/databricks/lakehouse-architecture/cost-optimization/best-practices

### Azure AI Services

#### Azure OpenAI Service

| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [Plan and manage costs for Azure AI Studio][AOAI-1]                | Microsoft                               | Nov 2023                 | Microsoft Learn \| Docs  |
| [Commitment tier pricing for Azure AI][AOAI-2]                     | Microsoft                               | Nov 2023                 | Microsoft Learn \| Docs  |
| [Plan to manage costs for Azure OpenAI Service][AOAI-3]            | Microsoft                               | Aug 2023                 | Microsoft Learn \| Docs  |
| [Azure Budgets and Azure OpenAI Cost Management][AOAI-4]           | [Shishir Garde][Shishir-Garde-1]        | Aug 2023                 | Microsoft Tech Community |
| [Calculating Chargebacks for Business Units/Projects Utilizing a Shared Azure OpenAI Instance][AOAI-5] | [Shikha Sinha][Shikha-Sinha-1]| Aug 2023 | Microsoft Tech Community |
| [Strategies for Optimizing High-Volume Token Usage with Azure OpenAI][AOAI-6] | [James Croft][James-Croft-1] | Dec 2023                 | Microsoft Tech Community |
| [Optimizing Azure OpenAI: A Guide to Limits, Quotas, and Best Practices][AOAI-7] | [Olga Molocenco-Ciureanu][Olga-Molocenco-Ciureanu-1]| Mar 2024             | Microsoft Tech Community |



[//]: <> (Azure OpenAI links)
[AOAI-1]: https://learn.microsoft.com/en-us/azure/ai-studio/how-to/costs-plan-manage
[AOAI-2]: https://learn.microsoft.com/en-us/azure/ai-studio/how-to/commitment-tier
[AOAI-3]: https://learn.microsoft.com/en-us/azure/cognitive-services/openai/how-to/manage-costs
[AOAI-4]: https://techcommunity.microsoft.com/t5/azure-governance-and-management/azure-budgets-and-azure-openai-cost-management/ba-p/3904833
[AOAI-5]: https://techcommunity.microsoft.com/t5/apps-on-azure-blog/calculating-chargebacks-for-business-units-projects-utilizing-a/ba-p/3909202
[AOAI-6]: https://techcommunity.microsoft.com/t5/fasttrack-for-azure/strategies-for-optimizing-high-volume-token-usage-with-azure/ba-p/4007751
[AOAI-7]: https://techcommunity.microsoft.com/t5/fasttrack-for-azure/optimizing-azure-openai-a-guide-to-limits-quotas-and-best/ba-p/4076268

### FOCUS
The `FinOps Cost and Usage Specification` (FOCUS™) is an open-source specification that defines clear requirements for cloud vendors to produce consistent cost and usage datasets.

It is founded to normalizes cost and usage datasets across cloud vendors and reduces complexity for FinOps Practitioners.

For more details read [here](https://focus.finops.org/).


| Topic                                                              | Author                                  | Published                | Channel                  |
| :-----------------------                                           | :-----------------------                | :----------------------- | :----------------------- |
| [FOCUS™ Datasets from Microsoft (Azure)][FOCUS-1]                  | Microsoft                               |                          | FinOps Foundation        |
| [FOCUS cost and usage details file schema][FOCUS-2]                | Microsoft                               | Jun 2024                 | Microsoft Learn \| Docs  |
| [FOCUS: A new specification for cloud cost transparency][FOCUS-3]  | [Michael Flanakin][Michael-Flanakin-2]                        | Oct 2023                 | Microsoft Azure Blogs    |
| [Democratizing FinOps: Transform your practice with FOCUS and Microsoft Fabric][FOCUS-4] | [Michael Flanakin][Michael-Flanakin-2]  | Nov 2023                 | Microsoft Azure Blogs    |
| [FOCUS: An open specification for cloud cost transparency][FOCUS-5] | [Michael Flanakin][Michael-Flanakin-1] | Jul 2024                 | Microsoft Tech Community |
| [Moving from FOCUS 1.0 preview to FOCUS 1.0][FOCUS-6]              | [Michael Flanakin][Michael-Flanakin-1]  | Jul 2024                 | Microsoft Tech Community |

[//]: <> (Storage links)
[FOCUS-1]: https://focus.finops.org/get-started/microsoft
[FOCUS-2]: https://learn.microsoft.com/en-us/azure/cost-management-billing/dataset-schema/cost-usage-details-focus
[FOCUS-3]: https://azure.microsoft.com/en-us/blog/focus-a-new-specification-for-cloud-cost-transparency
[FOCUS-4]: https://azure.microsoft.com/en-us/blog/democratizing-finops-transform-your-practice-with-focus-and-microsoft-fabric
[FOCUS-5]: https://techcommunity.microsoft.com/t5/finops-blog/focus-an-open-specification-for-cloud-cost-transparency/ba-p/4184578
[FOCUS-6]: https://techcommunity.microsoft.com/t5/finops-blog/moving-from-focus-1-0-preview-to-focus-1-0/ba-p/4184346


