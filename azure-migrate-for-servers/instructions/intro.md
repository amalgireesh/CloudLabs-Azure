# Introduction

Azure Migrate provides a central hub for discovery, assessment, and migration of on-premises workloads to Azure. The hub provides Azure Migrate tools, and well as integrated tools from independent software vendors (ISVs).

In this lab we will look at migrating your on-premises Hyper-V virtual machines to Azure using Azure Migrate. Any migration to the cloud should be preceded by a thorough assessment of your systems. Azure Migrate is the recommended assessment tool. This lab assumes an Azure migration project has already been created and dsicovery done to determine the machines that will be brought into Azure. 

In this lab we are going to look at the process involved to migrate a system we've previously assessed and determined is a good candidate to move to Azure. We will cover the following topics:

  * Setting up the source environment for migration to Azure
  * Setting up the Azure Migrate Assessment
  * Creating and enabling replication
  * Doing a Test Migration
  * Reviewing our migrated server