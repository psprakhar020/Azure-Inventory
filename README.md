# Script: Azure Inventory Script 

[![Build Status](https://dev.azure.com/psprakhar020/Azure_Inventory_Generate/_apis/build/status/psprakhar020.Azure-Inventory?branchName=master)](https://dev.azure.com/psprakhar020/Azure_Inventory_Generate/_build/latest?definitionId=1&branchName=master)

                                          
#          Date: Dec 13, 2018                                                                     
#          Author: Prakhar Sharma


# DESCRIPTION:
This script will pull the infrastructure details of the Azure subscriptions. Details will be stored under the folder "c:\AzureInventory"
If you have multiple subscriptions, a separate folder will be created for individual subscription.
CSV files will be created for individual services (Virtual Machines, NSG rules, Storage Account, Virtual Networks, Azure Load Balancers) inside the subscription's directory
