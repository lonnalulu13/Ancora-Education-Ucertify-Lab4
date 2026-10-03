# Ancora-Education-Ucertify-Lab4
# Taking a Full Backup

>**Original Lab Source**
>This lab was available through:
>[https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=1]

## Objective of the Lab In this lab
You will learn to take a full backup. During the full backup, the current status of the archive bit is ignored, everything is backed up, and the archive bit for each file is cleared. A full backup is the most appropriate for offsite archiving.

## Instructions
## STEP 1
Click the start menu and open Windows Administrative Tools.

## STEP 2
In the Administrative Tools window, in the right pane, scroll down, and double-click Windows Server Backup.

## STEP 3
In the wbadmin window, in the left pane, double-click Local Backup.

## STEP 4
In the right pane, under Actions, click Configure Performance Settings.

## STEP 5
In the Optimize Backup Performance dialog box, select the Custom radio button and in the Backup Option list, verify that Full backup is selected for all the displayed volumes and click OK.

### **Note**
A full backup takes the longest time and the most space to complete. However, if an organization only uses full backups, then only the latest full backup needs to be restored, meaning it is the quickest restore.

## STEP 6
In the right pane, click Backup Once.

## STEP 7
In the Backup Once Wizard window, perform the following steps:

a.At the Backup Options step, click Next.

b.At the Select Backup Configuration step, select the Custom radio button and click Next.

c.At the Select Items for Backup step, click Add Items.

d.In the Select Items dialog box, double-click Local disk (C):, scroll down, check the ip.txt checkbox, and then click OK.

e.Click Next twice.

f.At the Select Backup Destination step, from the Backup destination list, select New Volume (E:) and click Next.

g.At the Confirmation step, click Backup
### **CAUTION**
Wait till the backup process completes. It may take 15 to 20 minutes.

h.At the Backup Progress step, when Status is displayed as Completed, click Close.

## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
