Get Azure AD Password Protection Statistics
===========================================

            

WARNING: Due to retirement of Technet Script Gallery, migrated to:


[https://github.com/zjorz/Public-AAD-Scripts/blob/master/AAD-Password-Protection-Statistics.ps1](https://github.com/zjorz/Public-AAD-Scripts/blob/master/AAD-Password-Protection-Statistics.ps1)


 


So to gather the statistics through an AD forest I have written a script that gathers the statistics from the RWDCs that are part of the specified scope. The script supports, three modes being: forest,
 domain (specified) and rwdc (specified)! Independent of the scope, it also counts the total of every statistic property and presents it accordingly at the end or in the GridView through a separate entry at the end. You can therefore see the statistics per
 RWDC and in total. It also provides a CSV file with the info for later use in either Excel, GridView or some other way.


For more information, please see: [(2019-11-03) Azure AD Password Protection (A.k.a. Banned Password List) – Getting Statistics (Part 8)](https://jorgequestforknowledge.wordpress.com/2019/11/03/azure-ad-password-protection-a-k-a-banned-password-list-getting-statistics-part-8/)


-


For any questions or feedback use the Q&A of the script AND send me an e-mail through the following link: [Questions/Feedback](mailto:Jorge's Script Gallery <scripts.gallery@iamtec.eu>?subject=[Script Gallery Feedback:] 'REPLACE-THIS-PART-WITH-SOMETHING-MEANINGFULL')






 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
