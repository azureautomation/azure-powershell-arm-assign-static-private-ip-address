Azure Powershell ARM Assign Static Private IP address
=====================================================

            

 

 ![Image](https://github.com/azureautomation/azure-powershell-arm-assign-static-private-ip-address/raw/master/reip.jpg)

This script allows a user to update an existing Azure IaaS VM's Private Ip Address to a static IP. The script also reports the updated interface information for all VMs in the Resouce Group once the IP change has occurred. This
 script does accept pipeline inputs and can be used for batching updates of multiple VMs Ip addresses.


 


Example: .\ReIp.ps1 -VMName VM -ResourceGroupName RG -InterfaceName Nic1 -PvtIPNic 10.120.0.14


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
