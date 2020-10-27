Stop Windows Azure Virtual Machines on a Schedule
=================================================

            

[Windows Azure Scripting Center](http://www.windowsazure.com/en-us/documentation/scripts) |
[Get Started with Windows Azure PowerShell](http://go.microsoft.com/fwlink/?linkid=320929&clcid=0x409) |
[Windows Azure Infrastructure Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=infrastructure&service=all)

Description

Demonstrates stopping a single Virtual Machine or set of Virtual Machines (using a wildcard pattern) within a Cloud Service. It does this by creating scheduled tasks to stop the Virtual Machine(s) on a schedule at the time specified.

Example
 
Scenario
Suppose you have a test machine or set of test machines that you want turned off everyday at 5:30PM. This script will register the scheduled task to stop the virtual machines you specify.
Requirements

  *  PowerShell Version 3.0 
  *  Windows Azure PowerShell 0.6.19 
See Also

  *  Start-AzureVMsOnSchedule 
  *  [Windows Azure Infrastructure Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=infrastructure&service=all)

Script Content

The content of the script is reproduced below

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
