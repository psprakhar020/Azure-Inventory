# Script: Azure Inventory Script 
                                          
#          Date: Dec 13, 2018                                                                     
#          Author: Prakhar Sharma


# DESCRIPTION:
This is a script will pull the infrastructure details of the Azure subscriptions. Details will be stored under the folder "c:\AzureInventory"
If you have multiple subscriptions, a separate folder will be created for individual subscription.
CSV files will be created for individual services (Virtual Machines, NSG rules, Storage Account, Virtual Networks, Azure Load Balancers) inside the subscription's directory
