# Azure Managed Disk

In Microsoft cloud platform Microsoft Azure, a Managed Disk is a type of storage for virtual machines where Azure automatically handles the storage management for you.

## 1. First understand the problem (before Managed Disks)

When you create a Virtual Machine (VM) in Azure, it needs a disk to store:

- Operating system (Linux / Windows)
- Installed software
- Files and data

In the old Azure model, users had to manage storage accounts manually.

Example:

- Create a Storage Account
- Create VHD (Virtual Hard Disk) files
- Store them in the storage account
- Connect them to the VM

This was complicated and error-prone.

## 2. What is an Azure Managed Disk?

A Managed Disk means:

- Azure automatically creates and manages the storage account for your VM disk.
- You only manage the disk, not the storage infrastructure behind it.

So Azure handles:

- Storage accounts
- Disk replication
- Scaling
- Availability
