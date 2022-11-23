# Describe Cloud Service Types
This module covers the different cloud service types and shares some of the use cases and benefits aligned with each service type.

## Learning objectives
Upon completion of this module, you'll be able to:

- Describe Infrastructure as a Service (IaaS).
- Describe Platform as a Service (PaaS).
- Describe Software as a Service (SaaS).
- Identify appropriate use cases for each cloud service (IaaS, PaaS, SaaS).

## Prerequisites
Basic familiarity with IT terms and concepts

## This module is part of these learning paths
-   [Microsoft Azure Fundamentals: Describe cloud concepts](https://learn.microsoft.com/training/paths/microsoft-azure-fundamentals-describe-cloud-concepts/)

---

# Introduction
In this module, you’ll be introduced to cloud service types. You’ll learn how each cloud service type determines the flexibility you’ll have with managing and configuring resources. You'll understand how the shared responsibility model applies to each cloud service type, and about various use cases for each cloud service type.

## Learning objectives
After completing this module, you’ll be able to:

- Describe infrastructure as a service (IaaS).
- Describe platform as a service (PaaS).
- Describe software as a service (SaaS).
- Identify appropriate use cases for each cloud service (IaaS, PaaS, SaaS).

---

# Describe Infrastructure as a Service
Infrastructure as a service (IaaS) is the most flexible category of cloud services, as it provides you the maximum amount of control for your cloud resources. In an IaaS model, the cloud provider is responsible for maintaining the hardware, network connectivity (to the internet), and physical security. You’re responsible for everything else: operating system installation, configuration, and maintenance; network configuration; database and storage configuration; and so on. With IaaS, you’re essentially renting the hardware in a cloud datacenter, but what you do with that hardware is up to you.

## Shared responsibility model
The shared responsibility model applies to all the cloud service types. IaaS places the largest share of responsibility with you. The cloud provider is responsible for maintaining the physical infrastructure and its access to the internet. You’re responsible for installation and configuration, patching and updates, and security.

![shared-responsibility-b3829bfe](https://user-images.githubusercontent.com/94882786/202079863-95f24d51-af59-494f-be88-a9f6173b4c25.svg)

## Scenarios
Some common scenarios where IaaS might make sense include:

- Lift-and-shift migration: You’re standing up cloud resources similar to your on-prem datacenter, and then simply moving the things running on-prem to running on the IaaS infrastructure.
- Testing and development: You have established configurations for development and test environments that you need to rapidly replicate. You can stand up or shut down the different environments rapidly with an IaaS structure, while maintaining complete control.

---

# Describe Platform as a Service
Platform as a service (PaaS) is a middle ground between renting space in a datacenter (infrastructure as a service) and paying for a complete and deployed solution (software as a service). In a PaaS environment, the cloud provider maintains the physical infrastructure, physical security, and connection to the internet. They also maintain the operating systems, middleware, development tools, and business intelligence services that make up a cloud solution. In a PaaS scenario, you don't have to worry about the licensing or patching for operating systems and databases.

PaaS is well suited to provide a complete development environment without the headache of maintaining all the development infrastructure.

## Shared responsibility model
The shared responsibility model applies to all the cloud service types. PaaS splits the responsibility between you and the cloud provider. The cloud provider is responsible for maintaining the physical infrastructure and its access to the internet, just like in IaaS. In the PaaS model, the cloud provider will also maintain the operating systems, databases, and development tools. Think of PaaS like using a domain joined machine: IT maintains the device with regular updates, patches, and refreshes.

Depending on the configuration, you or the cloud provider may be responsible for networking settings and connectivity within your cloud environment, network and application security, and the directory infrastructure.

![shared-responsibility-b3829bfe](https://user-images.githubusercontent.com/94882786/202080071-cfffc73b-3010-42c2-8fd7-c6b28d432797.svg)

## Scenarios
Some common scenarios where PaaS might make sense include:

- Development framework: PaaS provides a framework that developers can build upon to develop or customize cloud-based applications. Similar to the way you create an Excel macro, PaaS lets developers create applications using built-in software components. Cloud features such as scalability, high-availability, and multi-tenant capability are included, reducing the amount of coding that developers must do.
- Analytics or business intelligence: Tools provided as a service with PaaS allow organizations to analyze and mine their data, finding insights and patterns and predicting outcomes to improve forecasting, product design decisions, investment returns, and other business decisions.

---

# Describe Software as a Service
Software as a service (SaaS) is the most complete cloud service model from a product perspective. With SaaS, you’re essentially renting or using a fully developed application. Email, financial software, messaging applications, and connectivity software are all common examples of a SaaS implementation.

While the SaaS model may be the least flexible, it’s also the easiest to get up and running. It requires the least amount of technical knowledge or expertise to fully employ.

## Shared responsibility model
The shared responsibility model applies to all the cloud service types. SaaS is the model that places the most responsibility with the cloud provider and the least responsibility with the user. In a SaaS environment you’re responsible for the data that you put into the system, the devices that you allow to connect to the system, and the users that have access. Nearly everything else falls to the cloud provider. The cloud provider is responsible for physical security of the datacenters, power, network connectivity, and application development and patching.

![shared-responsibility-b3829bfe](https://user-images.githubusercontent.com/94882786/202080144-aeab0e1e-9661-4659-9768-a23b374b7463.svg)

## Scenarios
Some common scenarios for SaaS are:

- Email and messaging.
- Business productivity applications.
- Finance and expense tracking.

---

# Knowledge check
Choose the best response for each question. Then select Check your answers.

## Check your knowledge
1. Which cloud service type is most suited to a lift and shift migration from an on-premises datacenter to a cloud deployment?

O - Infrastructure as a Service (IaaS)

X - Platform as a Service (PaaS)

X - Software as a Service (SaaS)

2. What type of cloud service type would a Finance and Expense tracking solution typically be in?

X - Infrastructure as a Service (IaaS)

X - Platform as a Service (PaaS)

O - Software as a Service (SaaS)

---

# Summary
In this module, you learned about the cloud service types and some common scenarios for each type. You also reinforced how the shared responsibility model determines your responsibilities with different cloud service types.

## Learning objectives
You should now be able to:

- Describe infrastructure as a service (IaaS).
- Describe platform as a service (PaaS).
- Describe software as a service (SaaS).
- Identify appropriate use cases for each cloud service (IaaS, PaaS, SaaS).

## This module is part of these learning paths
-   [Microsoft Azure Fundamentals: Describe cloud concepts](https://learn.microsoft.com/training/paths/microsoft-azure-fundamentals-describe-cloud-concepts/)
