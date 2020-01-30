![MIKES DATA WORK GIT REPO](https://raw.githubusercontent.com/mikesdatawork/images/master/git_mikes_data_work_banner_01.png "Mikes Data Work")        

# How To Uninstall an SQL Server Instance
**Post Date: November 10, 2016**        



## Contents    
- [About Process](##About-Process)  
- [Author](#Author)  
- [License](#License)       

## About-Process

<p>How to uninstall an SQL Server Instance from a mulit-instance Database Server.</p>

Step 1:
From the Database Server go to StartàRun, and type in appwiz.cpl.

![Go To AppWiz]( https://mikesdatawork.files.wordpress.com/2016/11/image0019.png "Go To AppWiz")
 
Step 2:
Locate the Database Server product you would like to uninstall. In this case we are selecting 'Microsoft SQL Server 2014 (64-bit)', and click 'Uninstall/Change'.

![Click Uninstall Change]( https://mikesdatawork.files.wordpress.com/2016/11/image0026.png "Click Uninstall Change")
 
Step 3:
Click 'Remove'.

![Select Remove]( https://mikesdatawork.files.wordpress.com/2016/11/image0032.png "Select Remove")
 
Be patient while the uninstall process begins…

![Setup Process]( https://mikesdatawork.files.wordpress.com/2016/11/image0042.png "Wait For Setup Process")
 
Step 4:
Select the Instance you wish to remove. In this case we are removing the SQL instance SQLSHARE09.
Click 'Next'.

![Select Instance Name]( https://mikesdatawork.files.wordpress.com/2016/11/image0052.png "Select Instance Name")
 
Step 5:
Select the Instance SQLSHARE09, and it's services:
Database Engine Services
Reporting Services – Native
DO NOT select Shared Features.
Click 'Next'.

![Select Features]( https://mikesdatawork.files.wordpress.com/2016/11/image0062.png "Select Features")
 
Step 6:
Click 'Remove'.

![Verify Features]( https://mikesdatawork.files.wordpress.com/2016/11/image0072.png "Verify Features")
 
Step 7:
Click 'Close'.

![Complete]( https://mikesdatawork.files.wordpress.com/2016/11/image0083.png "Complete")
 
You are done.
To confirm…
Check the Configuration Manager, or check under Services.
SQL Server Configuration Manager:
Simply open up the 'SQL Server Configuration Manager', and ensure the SQL Server Instance SQLSHARE09 is nolonger listed.

![Open Configuration Manager]( https://mikesdatawork.files.wordpress.com/2016/11/image0092.png "Open Configuration Manager")
 
The service name should not appear in the list. Here we see the service is missing therefore it has been successfully removed.

![Ensure Instance Has Been Removed]( https://mikesdatawork.files.wordpress.com/2016/11/image0102.png "Ensure Instance Has Been Removed")
 
Services:
StartàRun: Services.msc

![Go To Services]( https://mikesdatawork.files.wordpress.com/2016/11/image0111.png "Go To Services")
 
Look to see if the SQL Server (SQLSHARE09) Services is listed at all. All Database Services for SQLSHARE09 will not be present in the services list.

![Ensure Instance Was Removed]( https://mikesdatawork.files.wordpress.com/2016/11/image0121.png "Ensure Instance Was Removed")
 


[![WorksEveryTime](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://shitday.de/)

## Build-Info

| Build Quality | Build History |
|--|--|
|<table><tr><td>[![Build-Status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg?style=flat-square)](#)</td></tr><tr><td>[![Coverage](https://coveralls.io/repos/github/tygerbytes/ResourceFitness/badge.svg?style=flat-square)](#)</td></tr><tr><td>[![Nuget](https://img.shields.io/nuget/v/TW.Resfit.Core.svg?style=flat-square)](#)</td></tr></table>|<table><tr><td>[![Build history](https://buildstats.info/appveyor/chart/tygerbytes/resourcefitness)](#)</td></tr></table>|

## Author

[![Gist](https://img.shields.io/badge/Gist-MikesDataWork-<COLOR>.svg)](https://gist.github.com/mikesdatawork)
[![Twitter](https://img.shields.io/badge/Twitter-MikesDataWork-<COLOR>.svg)](https://twitter.com/mikesdatawork)
[![Wordpress](https://img.shields.io/badge/Wordpress-MikesDataWork-<COLOR>.svg)](https://mikesdatawork.wordpress.com/)
    
## License
[![LicenseCCSA](https://img.shields.io/badge/License-CreativeCommonsSA-<COLOR>.svg)](https://creativecommons.org/share-your-work/licensing-types-examples/)

![Mikes Data Work](https://raw.githubusercontent.com/mikesdatawork/images/master/git_mikes_data_work_banner_02.png "Mikes Data Work")

