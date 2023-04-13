# JanisonConfigToolsSelenium

# 1. PBTS

## 1.1 Exporting PBTS SIT tenant

AssessmentConfigExport.exe /config:PBTS_SIT.config

## 1.2 Creating a new PBTS SIT tenant

_Change "smita" and "xx" below to name the tenant as desired_

- Copy newpbts_sit.config as smitapbtsxx_alpha.config
- Edit smitapbtsxx_alpha.config and change 
- AssessmentTenantCreate.exe /config:smitapbtsxx_sit.config
- AssessmentConfigUpdate.exe /config:smitapbtsxx_sit.config

## 1.2 Creating a new PBTS ALPHA tenant

_Change "smita" and "xx" below to name the tenant as desired_

- Copy newpbts_alpha.config as smitapbtsxx_alpha.config
- AssessmentTenantCreate.exe /config:smitapbtsxx_alpha.config
- AssessmentConfigUpdate.exe /config:smitapbtsxx_alpha.config

