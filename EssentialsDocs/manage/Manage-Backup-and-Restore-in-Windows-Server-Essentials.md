---
title: "Manage Backup and Restore in Windows Server Essentials"
ms.custom: na
ms.date: 04/22/2014
ms.prod: windows-server-2012-r2-essentials
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
applies_to: 
  - Windows Server 2012 Essentials
  - Windows Server 2012 R2 Essentials
ms.assetid: 41000915-f6ff-4dbb-b7be-629ef36386d4
caps.latest.revision: 18
author: DonGill
manager: stevenka

---
# Manage Backup and Restore in Windows Server Essentials
 This topic applies to a server running Windows Server 2012 Essentials or Windows Server 2012 R2 Essentials, or to a server running Windows Server 2012 R2 Standard or Windows Server 2012 R2 Datacenter with the Windows Server Essentials Experience role installed.  
  
 Windows Server Essentials provides reliable ways to perform regular backups of your server and backups of your network computers. In the event of data loss, you can restore data from a successful backup on the server without restoring the entire computer. If necessary, you can perform a full system restore to your server or client computers in the network. The following table describes the different backup options available to you along with their advantages.  
  
|Backup Feature|Description|Advantages|  
|--------------------|-----------------|----------------|  
|Server Backup|Backs up your server running Windows Server Essentials. The data is backed up to an external USB drive.<br /><br /> For more information, see [Manage Server Backup](Manage-Server-Backup-in-Windows-Server-Essentials.md) and [Restore or repair your server](Restore-or-repair-your-server-running-Windows-Server-Essentials.md).|- Can restore files and folders on your server.<br /><br /> - Can perform full system restore of your server.|  
|Client Computer Backup|Backs up your client computers in the network. The data is backed up on the server running Windows Server Essentials.<br /><br /> For more information, see [Manage Client Backup](Manage-Client-Computer-Backup-in-Windows-Server-Essentials.md) and [Restore a full system from an existing client computer backup](Restore-a-full-system-from-an-existing-client-computer-backup.md).|- Can restore files and folders from your server.<br /><br /> - Can perform full system restore of your client computer.|  
| Microsoft Azure Backup|Performs an online backup of files or folders on your server. When you use  Azure Backup to back up server data, the information is encrypted by using your passphrase before it is uploaded to a secure datacenter on the Internet.<br /><br /> For more information, see [Manage Online Backup](Manage-Online-Backup-in-Windows-Server-Essentials.md).|- Can restore files and folders from your server.<br /><br /> - With incremental backups, only changes to files are transferred to the cloud.<br /><br /> - Backups are stored in  Microsoft Azure and are offsite, reducing the need to secure and protect onsite backup media.|  
  
## See also  
  
-   [Manage Windows Server Essentials](Manage-Windows-Server-Essentials.md)  
  
-   [Use Windows Server Essentials](../Topic/Use%20Windows%20Server%20Essentials.md)